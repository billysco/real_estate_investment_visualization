# real_estate_investment_visualization
Utilizing aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

# Usage
This project has 3 parts.  The first part is used to calculate and visualize housing units per year in San Francisco.  For the visualization, the data is represented by a bar chart. Next, the project analyzes sale price per square foot and average gross rent.  It then visualizes this data with a line plot of sale price per square foot and average gross rent.  This graph visualizes each neighborhood individually, and utilizes a dropdown to select the specific neighborhood for a more in depth analysis.  Finally, the data from the second part is parlayed into the third and final visualization, an interactive neighborhood map.  This interactive map gives users the ability to view the data on an actual map of San Francisco.  The information is also color coded for ease of interpretation.

# Technologies
This project is written in Python using jupyter notebook and uses the pandas, os, plotly, hvplot, pathlib, and dotenv libraries.  It also utilizes data from https://docs.mapbox.com/ for the interactive map.  Users will need to create a free account to get an api key.