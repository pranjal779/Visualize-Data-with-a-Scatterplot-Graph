# Visualize-Data-with-a-Scatterplot-Graph
Powered by D3js library

[Output](https://pranjal779.github.io/Visualize-Data-with-a-Scatterplot-Graph/)

## Project Overview
This project is a visualization of data pertaining to doping in professional bicycle racing, specifically highlighting the performance of cyclists in relation to allegations of doping. The main goal is to provide an interactive scatterplot graph that shows the correlation between a cyclist's race time and the year of their performance, along with indicating whether they had allegations of doping.  

## Features
Interactive Scatterplot: An SVG-based scatterplot that visually represents the data points of cyclists, showing the year of performance on the x-axis and the race completion time on the y-axis.
- Tooltip Information: On hovering over any data point, a tooltip appears providing detailed information about the cyclist, including their name, time, year, and whether they had doping allegations.
- Color-Coded Data Points: Cyclists with doping allegations are marked with orange dots, while those without allegations are marked with green dots for easy differentiation.
- Responsive Design: The graph is designed to be responsive and adjusts according to the screen size, providing a good user experience on different devices.

## Technology Stack
- HTML: For structuring the content of the webpage.
- CSS: For styling the page, including the scatterplot and tooltip.
- JavaScript: For fetching the data, creating the scatterplot, and handling user interactions.
- D3.js: A powerful JavaScript library for creating dynamic and interactive data visualizations in web browsers.

## How It Works
- Data Fetching: The project fetches data from a remote JSON file hosted on GitHub, which contains information about various cyclists, including their performance year, time in seconds, and doping allegations.
- Scales and Axes: D3.js is used to generate scales based on the data, mapping the year to the x-axis and the race time to the y-axis.
- Drawing the Graph: Circles are plotted on the SVG canvas representing each cyclist's data. The position of each circle is determined by the year and time values, and the color is determined by the presence or absence of doping allegations.
- Interactivity: Tooltips provide additional information on hover, making the data easily accessible and informative.

## Data Source
The data for this project is sourced from a publicly available JSON file provided by freeCodeCamp. It includes the following fields for each cyclist:

- Name: The name of the cyclist.
- Year: The year of the performance.
- Time: The time taken to complete the race.
- Seconds: The time in seconds for easy plotting.
- Doping: Information about doping allegations.

# Conclusion
This project demonstrates the power of data visualization in uncovering patterns and insights in a dataset. By using D3.js and basic web technologies, it provides an interactive and informative visualization that highlights the impact of doping allegations on professional cycling.

