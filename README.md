# belly-button-challenge
Module 14 Challenge

# Belly Button Biodiversity Dashboard
This interactive project explores the microbial species found in human navels using the Belly Button Biodiversity dataset. The dataset reveals that a small number of microbial species (OTUs) are present in over 70% of individuals, while others are relatively rare.

# Project Overview
The dashboard enables users to investigate the dataset interactively. Key features include:
A bar chart displaying the top 10 OTUs for a selected individual.
A bubble chart visualizing the distribution of all OTUs in the chosen sample.
A panel showcasing demographic information for the selected individual.
A dropdown menu for dynamic updates to all visualizations.

# Files and Folders
The repository consists of:
static/js/app.js: JavaScript code managing the dashboard.
index.html: The main HTML file for the dashboard.
samples.json: A sample data file.

# Key Features
Horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
Use sample_values as the values for the bar chart.
Use otu_ids as the labels for the bar chart.
Use otu_labels as the hovertext for the chart.

Bubble Chart: That displays each sample.
Use otu_ids for the x values.
Use sample_values for the y values.
Use sample_values for the marker size.
Use otu_ids for the marker colors.
Use otu_labels for the text values. 

Display the sample's metadata, i.e., an individual's demographic information.
Loop through each key-value pair from the metadata JSON object and create a text string.
Append an html tag with that text to the #sample-metadata panel.

# Functionality
Data Retrieval: The D3 library fetches data from a JSON file hosted at https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
Visualization Creation: Plotly generates and updates bar and bubble charts within the dashboard.
Interaction: Users can select a sample ID from a dropdown menu, triggering updates to charts and metadata.

# Local Execution
Clone the repository: git clone https://github.com/your-username/belly-button-biodiversity.git
Navigate to the project directory: cd belly-button-biodiversity
Open index.html in your web browser.

# Technologies
JavaScript
D3.js and Plotly.js
HTML
JSON

# License
The project is licensed under the MIT License.

# Contributions
Contributions are welcome via issues or pull requests.