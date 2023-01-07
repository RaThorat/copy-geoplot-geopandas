# copy-geoplot-geopandas
## copied code to plot a map with geoplot and geopandas

This code is using the geopandas and geoplot libraries to visualize and analyze geographical data. It begins by importing and reading in three datasets: a dataset of world map data, a dataset of NYC borough data, and a dataset of NYC collisions data.

It then uses the geoplot.polyplot function to create a map of the world, and uses the Orthographic projection to display it as a globe. The code also uses mapclassify to create a scheme for dividing the data by GDP per person and geoplot.choropleth to create a choropleth map of the data.

The code also creates a cartogram of Africa using the geoplot.cartogram function, and a kernel density estimate plot of NYC collisions using the geoplot.kdeplot function. It also creates a Voronoi diagram of NYC collisions using the geoplot.voronoi function. All of these plots are overlaid on top of the NYC borough data for context.
