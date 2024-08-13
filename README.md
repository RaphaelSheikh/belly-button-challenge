# Belly Button Biodiversity

![image](https://github.com/user-attachments/assets/81b36518-6779-4512-b300-0df0c41c3d76)

# Background

Build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

# Instructions

1. Use the D3 library to read in **`samples.json`** from the URL **`https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`**.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    * Use **`sample_values`** as the values for the bar chart.

    * Use **`otu_ids`** as the labels for the bar chart.

    * Use **`otu_labels`** as the hovertext for the chart.

![image](https://github.com/user-attachments/assets/77c13acd-967f-42f0-9383-5d703c9406e9)

3. Create a bubble chart that displays each sample.

    * Use **`otu_ids`** for the x values.

    * Use **`sample_values`** for the y values.

    * Use **`sample_values`** for the marker size.

    * Use **`otu_ids`** for the marker colors.

    * Use **`otu_labels`** for the text values.
  
![image](https://github.com/user-attachments/assets/b45dd06f-29b5-435a-9c12-a26e503f5cfe)

4. Display the sample's metadata, i.e., an individual's demographic information.

    * Loop through each key-value pair from the metadata JSON object and create a text string.

    * Append an html tag with that text to the **`#sample-metadata`** panel.
  
![image](https://github.com/user-attachments/assets/5d425fb6-195f-43cc-99dd-4c99e82226eb)

5. Update all the plots when a new sample is selected.

![image](https://github.com/user-attachments/assets/c828d4dd-123a-4cf5-8e5d-8a0404e2ecf3)

6. Deploy

# References

* Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. (http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

* JSON HTML (https://www.w3schools.com/Js/js_json_html.asp)

* The JavaScript library for bespoke data visualization (https://d3js.org/)

* Interactive Data Visualizations in JavaScript (https://www.geeksforgeeks.org/interactive-data-visualizations-in-javascript/)

* D3.js (https://www.tutorialspoint.com/d3js/index.htm)
