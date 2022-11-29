# App to see the historical fire in Uruguay with FIRMS 

This is a beta version (November/2022) for monitoring fires using FIRMS data

The Earth Engine version of the Fire Information for Resource Management System (FIRMS) dataset contains the LANCE fire detection product in rasterized form. The near real-time (NRT) active fire locations are processed by LANCE using the standard MODIS MOD14/MYD14 Fire and Thermal Anomalies product. Each active fire location represents the centroid of a 1km pixel that is flagged by the algorithm as containing one or more fires within the pixel. The data are rasterized as follows: for each FIRMS active fire point, a 1km bounding box (BB) is defined; pixels in the MODIS sinusoidal projection that intersect the FIRMS BB are identified; if multiple FIRMS BBs intersect the same pixel, the one with higher confidence is retained; in case of a tie, the brighter one is retained.


The app can be accessed at:
https://lucassantarosa.users.earthengine.app/view/fire-monitoring-uy-test
