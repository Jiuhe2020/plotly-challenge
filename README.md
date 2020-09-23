# Belly Button Biodiversity
## Deployment Link
https://jiuhe2020.github.io/plotly-challenge/

## Challenge Instructions
This project utilizes Javascript, HTML and Ploty to create an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.\

## Plotly Charts
1. D3 library was used to read in `samples.json`.
2. A horizontal Bar Chart with a dropdown menu was generated to display the top 10 OTUs found in that individual.
- Used `sample_values` as the values for the bar chart.
- Used `otu_ids` as the labels for the bar chart.
- Used `otu_labels` as the hovertext for the chart.
3. A Bubble Chart that displays each sample was created.
- Used `otu_ids` for the x values.
- Used `sample_values` for the y values.
- Used `sample_values` for the marker size.
- Used `otu_ids` for the marker colors.
- Used `otu_labels` for the text values.
4. The sample metadata was displayed in a format of key-value pair from the metadata JSON object as each individual's demographic information.
5. BONUS: A Gauge Chart was created to plot the weekly washing frequency of the individual.
6. All of the plots will be updated when a new sample is selected.

---
### Copyright
Jiuhe Zhu © 2020. All Rights Reserved.
