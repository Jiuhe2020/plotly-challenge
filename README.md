# Belly Button Biodiversity
![Bacteria](https://www.fertilitycenter.com/wp-content/uploads/2017/07/iStock-518090962.jpg)

## Deployment Link
https://jiuhe2020.github.io/plotly-challenge/

## Challenge Instructions
This project utilizes Javascript, HTML5 and Plotly to create an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Plotly Charts
- D3 library was used to read in `samples.json`
- A horizontal Bar Chart with a dropdown menu was generated to display the top 10 OTUs found in that individual
  - Used `sample_values` as the values for the bar chart
  - Used `otu_ids` as the labels for the bar chart
  - Used `otu_labels` as the hovertext for the chart
<p align="center">
  <img src="https://github.com/Jiuhe2020/plotly-challenge/blob/master/images/Plotly_BarChart.png" height="50%" width="50%">
</p>

- A Bubble Chart that displays each sample was created
  - Used `otu_ids` for the x values
  - Used `sample_values` for the y values
  - Used `sample_values` for the marker size
  - Used `otu_ids` for the marker colors
  - Used `otu_labels` for the text values
<p align="center">
  <img src="https://github.com/Jiuhe2020/plotly-challenge/blob/master/images/Plotly_BubbleChart.png" height="50%" width="50%">
</p>

- The sample metadata was displayed in a format of key-value pair from the metadata JSON object as each individual's demographic information
<p align="center">
  <img src="https://github.com/Jiuhe2020/plotly-challenge/blob/master/images/Demographic_Info.png" height="30%" width="30%">
</p>

- BONUS: A Gauge Chart was created to plot the weekly washing frequency of the individual.
<p align="center">
  <img src="https://github.com/Jiuhe2020/plotly-challenge/blob/master/images/Plotly_GaugeChart.png" height="30%" width="30%">
</p>

- All of the plots will be updated when a new sample is selected.
<p align="center">
  <img src="https://github.com/Jiuhe2020/plotly-challenge/blob/master/images/Dashboard.png">
</p>

---
### Copyright
Jiuhe Zhu © 2020. All Rights Reserved.
