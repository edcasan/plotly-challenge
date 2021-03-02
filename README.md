https://edcasan.github.io/plotly-challenge/

Belly Button Biodiversity.

Built an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Plotly
- Using the D3 library to read in samples.json,
- Creation a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual,
- Used sample_values as the values for the bar chart,
- Used otu_ids as the labels for the bar chart,
- Used otu_labels as the hovertext for the chart,
- Creation a bubble chart that displays each sample,
- Used otu_ids for the x values,
- Used sample_values for the y values,
- Used sample_values for the marker size,
- Used otu_ids for the marker colors,
- Used otu_labels for the text values,
- Deployment the sample metadata, i.e., an individual's demographic information,
- Deploymeny each key-value pair from the metadata JSON object somewhere on the page,
- Updated all of the plots any time that a new sample is selected,
- Adapted the Gauge Chart for values ranging from 0 through 9,
- Updated the chart whenever a new sample is selected,

![image](https://user-images.githubusercontent.com/63757160/109660693-c512fc80-7b2e-11eb-8664-6d401f9c55db.png)

![image](https://user-images.githubusercontent.com/63757160/109660778-deb44400-7b2e-11eb-84ad-aa0ba2621a45.png)

