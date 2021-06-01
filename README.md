# D3-Challenge
This repository contains the code files for a data visulation of health risk factors using 2014 data from the US Census Bureau. The information plotted is a scatter plot showing the relationship between median household income and obesity percentage at the state level.

The graph is created using JavaScript D3.

The JavaScript code first designates the chart size and margins to create the plot area in the HTML document.

Next the data in the csv file is imported and the data and obesity entries are cast as numerical values to ensure they are graphed properly.

Scale functions are created based on the ranges of the data points found in the csv file.

The data points are displayed as circles on the graph. The code uses the data in the csv file and the scale fucntions to place a circle at the appropriate loaction on the chart area.

The states abbreviation is then added to center of each circle.

The graph also uses the toolTip to display the state name, median household income, and obesity percentage when the mouse is hovered over an individial states circle on the graph. The toolTip is setup to display the information when the mouse cursor hovers over the circle, and disappears the mouse cursor leaves the area.
