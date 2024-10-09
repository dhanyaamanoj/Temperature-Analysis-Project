# Temperature-Analysis-Project
This project utilizes a subset of The National Centers for Environmental Information (NCEI) Daily Global Historical Climatology Network (GHCN-Daily) dataset. The dataset contains daily temperature records from various land surface stations across the globe. The primary goal of this project is to analyze temperature variations over time and visualize the findings effectively. 

The following datasets are used in this project:
1. Temperature.csv: Contains daily temperature records with columns for station ID, date, element type (TMAX/TMIN), and temperature values (in tenths of degrees Celsius).
2. BinSize.csv: Contains metadata about weather stations, including their geographic coordinates.

## Libraries Used
This project utilizes the following libraries:
- **Pandas**: For data manipulation and analysis, providing data structures like DataFrames.
- **Matplotlib**: For basic plotting and visualization of data.
- **Seaborn**: For creating attractive statistical graphics and enhancing Matplotlib visualizations.
- **Geopandas**: For handling geospatial data and performing spatial operations.
- **Folium**: For creating interactive maps to visualize geospatial data.

## Objectives
Task 1: : Plot a line graph of the record high and low temperatures by day of the year over the period 2005-2014, shading the area between the highs and lows.
Steps:
Convert the Date column to a day-of-year format, ignoring leap years.
Separate the TMAX and TMIN data.
Calculate record highs and lows for each day of the year.
Plot the record high and low temperatures using matplotlib.
Shade the area between the high and low records.
Output: The graph visualizes temperature trends and highlights extreme values over over the period 2005-2014.

Task 2. Overlay scatter points for any temperature records from 2015 that broke the previous highs or lows.
Steps:
Extract temperature data for 2015.
Identify any 2015 temperature records that exceeded the 2005-2014 records.
Overlay scatter points on the existing graph to highlight these records.

Task 3: Exclude Leap Days
Goal: Ensure that February 29th is excluded from the analysis to maintain consistency across the year.

Task 4: Visualize Weather Station Locations: Plot the locations of weather stations on a map for spatial analysis.
Steps:
Use Folium to create an interactive map centered around the relevant geographic area.
Add markers for each weather station, displaying relevant temperature information in popups.

Task 5: Plot Temperature Summary for Ann Arbor (2015): Create a temperature summary specifically for Ann Arbor in the year 2015.
Steps:
Filter data for Ann Arbor for the year 2015.
Calculate the mean, maximum, and minimum temperatures.
Interactive Map displays weather stations near Ann Arbor, Michigan, for the year 2015. 
Each station is marked with popups showing key temperature summaries, including mean, maximum, and minimum temperatures.
A heatmap visualizes the distribution of average temperatures recorded by weather stations around Ann Arbor in 2015.
The heatmap uses a color gradient (from blue to red) to represent temperature intensity, providing an intuitive view of temperature variations across the region.






