# Major Assignment 2: Geospatial Visualizations

**Done by:** Pawan  
**Course:** Data Visualization - Fall 2024

## Overview
This visuualization presents three interactive choropleth maps of Massachusetts, visualizing population and inequality data. The maps were created using D3.js, TopoJSON, and GeoJSON, and are organized in a single, vertically centered page for clarity. This page is hosted as a GitHub webpage, ensuring easy access and viewing.

## Assignment Objectives
- Familiarize with various map projection methods and their significance in geospatial visualization.
- Use color coding to convey data insights effectively through different scales.
- Process and filter data for visualization readiness.
- Design an accessible, visually appealing static webpage on GitHub.

## Geospatial Visualizations

1. **MAP A - Actual Population in 1980**  
   - **Description:** Displays Massachusetts towns' population data from 1980.

2. **MAP B - Population Change (1980-2010)**  
   - **Description:** Visualizes the population change between 1980 and 2010 for each town.
   - **Interaction:** Towns highlight on hover, displaying interactive tooltips.

3. **MAP C - Gini Index by County (2019)**  
   - **Description:** Shows county-level income inequality for 2019, color-coded by Gini Index.
   - **Tooltip:** On hover, displays a tooltip with Gini Index data for each county.

## Additional Features

- **Tooltip DIV Element:** Displays additional context on MAP C with Gini Index data for each year in each county.
- **Bonus:** Added a temporal line chart for Gini Index changes over time in the tooltip of MAP C, focusing on data accuracy and visualization clarity.
  
## Styling and Presentation

- **Page Layout:** Three maps in a vertically ordered layout, styled with Flexbox for horizontal centering.
- **Title and Author Information:** Page includes a title (H1) and author's name (H3), both styled for a professional appearance.
- **Color Schemes and Fonts:** Thoughtful use of colors, fonts, and layout for a clear, engaging user experience.
- **GitHub Hosting:** The completed webpage is hosted on GitHub for easy access.

## How to View
The webpage can be accessed publicly through the GitHub Pages link associated with this repository. Ensure the `data` folder contains only the necessary TopoJSON and CSV files for smooth performance.
