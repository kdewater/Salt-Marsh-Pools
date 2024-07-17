17 June, 2024. This code is associated with a publication that will be updated when the manuscripts are published and available online. 


The code was developed in 2023 to calculate salt marsh pool expansion on 12 Maine salt marshes by Katelyn DeWater at the University of New England. This script requires many inputs that are combined to compute expansion, count, and elevations. Regretfully, you will not be able to run the script on your own without these specific inputs (see file paths in the jupyter notebook). If you are interested in working with this script on your own, please feel free to contact me (kdewater1511@gmail.com), and I can help you, gladly. I make this script available for complete transparency and ban code is better than no code. I am happy to answer any questions about these scripts. 


This repository has 4 scripts:


‘Pool_Expansion.ipynb’ will compute the percent cover of pools and will generate a plot of expansion from 2009 to 2021. 
‘Pool_Density.ipynb’ will compute the number of pools per square kilometer of marsh and will generate a plot of density from 2009 to 2021. 
‘Pool_Changes_Intersection.ipynb’ will compute how the pools have changed over time based on how they overlap. For example, if one pool overlaps with more than one pool, it split apart. This will generate a graph of how the pools have changed over time and the percent change in pool cover grouped by type of change. 
‘PoolSize_Elevation_SeaLevel.ipynb’ will compute the pool size based on pool type, pool elevation, and parts of the script to get marsh elevations. This also generates a graph of pool size compared to elevation. This will compute the relative rate of sea level rise from data from the Portland, ME NOAA tide gauge. 


I apologize that this code is not commented or well documented, and you will not be able to run it without the file structures that exist on my computer. Many of these scripts were generated with the aid of ChatGPT. However, please reach out, and I am happy to help you with whatever relevant project you may be working on. The script is unlikely to be updated as it is the script for a specific project and will need to be written differently for future projects. If you need to make these types of calculations, it will be much easier to write a script on your own than to use these scripts. 


See https://dune.une.edu/gis_data/1/ for 2009 and 2021 pool geopackage data files. 
See NOAA Data Access Viewer for 2020 lidar-derived DEM data for each marsh. 
If there are any other files that could be of use, please reach out, and I would be happy to share them with you. 

