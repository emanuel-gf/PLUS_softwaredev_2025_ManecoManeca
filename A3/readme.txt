-- README

For this, I explored the integration of Earth Data Hub and then explored other CRS to plot climate data over large scale size

The pain in the ass was first understand about the connection with Earth Data Hub. It is not so simple as it seens and took me a time to set it up.
To facilitate I created a code to deal with key registration.

And another time-consuming part was to deal with the ERA5 data. Even though is organized through xarray dataset, there is a lot of transformations
in order to process the data for the plot. 
The subsampling approach come when I found a similar analysis at the Earth Data Hub, few people have been sharing notebooks there. 

By the end, the matplotlib have a lot of specificities which are not the easiest way, I far prefer ggplot in R to create stunning things than matplotlib. 
However it seens that the pythonical ideology is being well accept between a broad range of niches.

