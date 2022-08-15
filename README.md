# Data Visualization

## Description

In this project assignment, a data set containing information on earthquakes in Croatia from the period 2000 to 2022 is visualized. For each earthquake, data is listed in order: year, latitude, longitude, magnitude (size), group (light, small, moderate, strong), location.

The goal of the visualized data set is to enable an overview of all earthquakes in Croatia from the period 2000 to 2022 in a simple, comprehensible and presentable way.

## Features

Information is available in the form of a bar graph on the number of each group of earthquakes for a specific year and their appearance in the form of circles on the geographic map of Croatia. The size of the circle is determined by the magnitude of the earthquake.

Hovering the mouse over one of the columns of the bar graph displays the exact number of earthquakes and the magnitude range for the corresponding group, and only the circles representing the group of that column remain on the geographic display. By clicking on the column, the mentioned view is preserved.

Hovering the mouse over the circle on the geographic view shows the recorded location of the earthquake and the exact amount of magnitude.

The geographic view can be scrolled and zoomed to improve its clarity.

There is one button for each year, and clicking on each one refreshes the bar graph and the geographical display of the corresponding year.

Clicking on the 'play' button refreshes the bar graph and geographic display for the next year every two seconds, and after 2022 the refresh continues from the earliest available year 2000. The above can be stopped by clicking the 'pause' button.

## Technologies Used

In this project, data visualization is realized using the HTML presentation language for creating web pages, the CSS style language, the JavaScript programming language, and the most important JavaScript library for producing dynamic, interactive data visualizations in web browsers D3.js.

The final data used for visualization is written in JSON format. JSON is an open standard file format and data interchange format that uses human-readable text to store and transmit object data consisting of attribute-value pairs and strings.

The realization of the geographical representation of Croatia was carried out using GeoJSON records. GeoJSON is an open standard format designed to represent simple geographic features, along with their non-spatial attributes. It is based on the JSON format.
