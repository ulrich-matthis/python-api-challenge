#Note: world map visualizations are not loading into github; however, they are functional within VSCode and jupyter notebook

# python-api-challenge

For this weeks challenge there were two objectives to be completed using two different API keys. The first task can be viewed within
the WeatherPy folder which was to compile a list of locations and record them into a dataframe with other pertinent information, such
as Max Temperature, Country, Humidity and Cloudiness to name a few of them. The data was also exported as a file to use for part two of 
the assignment. Following data collection multiple scatter plots were created to visualize variables recorded at each latitude for the locations.
Scatter plots were also created for each hemisphere, by setting the northern hemisphere at greater than or equal to 0 and the southern at less than
0. Brief analysis for each group of plots is provided within the code in this folder.

Part 2 of this project used the exported file from the first part and used an API key to pull hotel data for each coordinate recored in the data file.
Prior to the use of the key, the dataframe was filtered down to the optimal criteria and following the filtering of the data the API was used to find
the closest hotel within 10000 meters of the coordinate. If none were available, "No Hotel Found" was displayed in the result as they were appended to the
data set. Map visuals were created within the code for the entire data frame from the initial file, a second visual was created for the final locations
and hotel name, if available, was displayed when the location is hovered over.
