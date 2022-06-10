# Mass_shooting_Visualization
Using the "US Mass Shootings" dataset found on kaggle (https://www.kaggle.com/datasets/zusmani/us-mass-shootings-last-50-years)
I created a map visualizing where they took place and how severe they were.

 -Cleaning data
Many of the datapoints were missing coordinates,
so i used geopy and Bing Maps to fill in those missing values.

- visualizing
I used Geoviews to visualize the data, making points appear larger
or smaller depending on the number of victims. Using hovertools,
you can view more information by hovering over a point.

