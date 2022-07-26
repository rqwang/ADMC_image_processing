# MATLAB video processing 
to support the paper ten Pas et al. (doi: https://doi.org/10.1101/2022.06.14.496157):

Author: Chad ten Pas

Description: This script processes a folder of images and finds the meniscus height relative to a reference length in each image. It uses a canny edge
detection that is tunable to find edges. The images are then cropped down to reduce data. The centroid is calculated and converted to height data.

Uploaded by Roger Wang (rq.wang@rutgers.edu)
 
Update: 

(07/21/2021) Added scripting to find the initial height before pressure application. Added pressure processing

(08/29/2021) Added automation to select reference for pixel conversions and processing data.
