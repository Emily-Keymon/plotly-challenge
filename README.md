# Belly Button Biodiversity Analysis
The goal of this project was to use JavaScript to present interactive visualizations of belly button biodiversity data within a web page. Since the baseline data was provided in JSON format, D3 was used to import and process the data, while Plotly was used to generate the required visualizations.

---
## Data Sources
* http://robdunnlab.com/projects/belly-button-biodiversity/

---
## Tools Used
* PyCharm 
* HTML/CSS/Bootstrap
* JavaScript = Plotly, D3

---
## Tasks
## Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

6. Update all of the plots any time that a new sample is selected.

---
## Results
## Website:  https://emily-keymon.github.io/Belly-Button-Biodiversity-Analysis/

![screenshot](https://user-images.githubusercontent.com/64673015/94349818-d69b2a00-000d-11eb-8c6b-a94bed937a13.PNG)

---
### About the Data
Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

- - -

