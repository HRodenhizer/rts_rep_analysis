# rts_rep_analysis
This repository hosts code to analyze the distribution of polygons in the ARTS data set across the environmental space of the permafrost region.

Files with "v.1.0.1_old" in the name represent results from model training with most of ARTS, but that erroneously excluded some negative points where the vector bounding box did not cover the center of a raster cell during conversion to raster format.
Files with "v.1.0.1_filter" in the name represent results from model training with any ARTS points within 100 km of a positive RTS observation.
Files with only "v.1.0.1" in the name represent results from model training with all of ARTS.
