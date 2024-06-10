# Belly Button Biodiversity Dashboard

## Project Overview

This project is an interactive dashboard that explores the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species were present in more than 70% of people, while the rest were relatively rare.

The dashboard allows users to select different samples and view the top 10 Operational Taxonomic Units (OTUs) for that individual in a bar chart, as well as visualize all OTUs in a bubble chart. Additionally, it displays the demographic information for the selected individual.

## Features

- **Interactive Dropdown Menu**: Select a test subject ID number to view corresponding data.
- **Bar Chart**: Displays the top 10 OTUs found in the selected individual.
- **Bubble Chart**: Shows the distribution of all OTUs for the selected individual.
- **Demographic Info Panel**: Displays demographic information for the selected individual.

## Files

- `index.html`: The main HTML file that contains the structure of the dashboard.
- `static/js/app.js`: The JavaScript file that loads data, builds charts, and updates the dashboard.
- `static/css/style.css`: The CSS file for styling the dashboard.
- `samples.json`: The dataset used for the dashboard (hosted externally).

## Technologies Used

- **HTML**: For structuring the webpage.
- **CSS**: For styling the dashboard.
- **JavaScript (D3.js & Plotly.js)**: For data manipulation and visualization.
- **Bootstrap**: For responsive layout and styling.

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Nicolerennie25/belly-button-challenge.git
    ```
2. Navigate to the project directory:
    ```bash
    cd belly-button-challenge
    ```
3. Open `index.html` in your web browser.

### Deployment

This project is deployed using GitHub Pages. 
## Acknowledgments

- The dataset used in this project is provided by the Belly Button Biodiversity dataset.
