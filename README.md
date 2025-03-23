# Land-parcel-optimization

This project reads a shape file of land parcel polygons with specified carbon stores and costs. Its purpose is to filter out ouliers that are too small, and find a subset of parcels that maximize the total carbon store, while also ensuring that the total cost of the subset is no more than 50% of the total cost, and that no chosen parcels is adjacent to another chosen parcel.

This project uses geopandas to analyse the data, matplotlib to plot, and pulp to solve the optimization problem. For the full list of packages, see the requrements.txt file.
