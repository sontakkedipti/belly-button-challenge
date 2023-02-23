In this assignment, built an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Used the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
![Website](https://user-images.githubusercontent.com/112952607/220961465-061d4901-e75f-4346-bcff-725f3f6ec301.png)

Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
Used sample_values as the values for the bar chart.
Used otu_ids as the labels for the bar chart.
Used otu_labels as the hovertext for the chart.

![horizontal bar chart](https://user-images.githubusercontent.com/112952607/220961510-49f450d4-f74e-46b0-b7db-d9de31064d87.png)


Bubble Chart
Created a bubble chart that displays each sample.
Used otu_ids for the x values.
Used sample_values for the y values.
Used sample_values for the marker size.
Used otu_ids for the marker colors.
Used otu_labels for the text values.

Bubble Chart
Displayed the sample metadata, i.e., an individual's demographic information.
Displayed each key-value pair from the metadata JSON object somewhere on the page.

![Bubble](https://user-images.githubusercontent.com/112952607/220961727-8aa6a954-3d67-438a-8b84-b38eeb979f11.png)


Gauge Chart
Adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.
Modified the example gauge code to account for values ranging from 0 through 9.
Updated the chart whenever a new sample is selected.
Weekly Washing Frequency Gauge.

![Gauge chart](https://user-images.githubusercontent.com/112952607/220961759-6830a67a-842c-4f44-b39d-50f2d2dcb127.png)

Used below App to develop this website<p>
Javascript<br>
Json <br>
HTML<br>
CSS<br>

