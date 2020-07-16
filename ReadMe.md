# Pyviz Project

In this project we are visualizing the Toronto housing martket from 2001 to 2016. Prior to running the code you need an API Key from [MapBox](https://www.mapbox.com/) stored in an enviromnet variable as follows:

mapbox = "Your API Key"

The Project is divided up as follows. The rental analysis notebook has all the inidividual plot as well as data manipulation and the resulting dataframes. That data is the taken into the dashboard notebook which is where the construction of the notebook takes place.

The final Dashboard looks like this, as you can see three of the plots did not show up (neighbourhood_map, average_house_value_snapshot, sunburts_cost_analysis), but they can be viewed under the debug or in the rental analysis with the exception of the sunburst plot which I was unable to get to show properly. 

![Dashboard](dashboard.GIF?raw=true "Dashboard")

## Dependencies:
pandas
matplotlib
hvplot
plotly
Panels



