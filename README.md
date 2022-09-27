# color_clusters
***exploratory code!*** *:an attempt to segment and model veins by k means color clustering and polar coordinate conversion*
ultimately, the segmenting of veins and conversion to polar coordinates would allow modeling of veins

in the notebook:
- read in image of a grapevine leaf
- perform k means clustering on pixel color values
- reassign pixel values to k means centroid values
- convert to polar coordinates
- create grayscale image with just vein pixels
- iteratively erode and record how many erosions until each pixel disappears to segment veins
