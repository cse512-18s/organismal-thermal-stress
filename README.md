# Visualizing Organismal Thermal Stress
[Tony Cannistra](anthonycannistra.com)

## Summary Proposal 

Anthropogenic climate change is having a dramatic effect on earth’s natural systems. To maintain functional ecosystems and preserve biodiversity in this changing world, the conservation community has come to rely on computational models to inform decision making. One particular class of model, known as a “biophysical model,” uses mathematical representations of energy balance and organism-environment heat transfer to translate environmental conditions into organismal body temperatures. From laboratory experiments with myriad cold-blooded species (that is, organisms that rely on behavior and the environment for temperature regulation), we know that organisms are sensitive to certain body temperature thresholds (”biophysical thresholds”) above or below which their performance (i.e. ability to eat, move, reproduce) is limited. When an organism’s body temperature crosses one of these thresholds (i.e. goes below a lower threshold or above a high threshold), we consider the organism to be experiencing “thermal stress.”

From our lab in the Department of Biology I have access to several decades of daily (noontime) body temperature values for several cold-blooded species (butterflies/lizards) in a 30km grid across the state of Colorado. By applying a biophysical threshold to these body temperatures, we can obtain a binary thermal stress classification. For this project I intend to visualize the spatial and temporal dimensions of this thermal stress. Are there locations which are particularly stressful for organisms? What percentage of an organisms’ known range is experiencing stressful conditions today/this year/this decade? Working in collaboration with my advisor Dr. Lauren Buckley, I intend to build a visualization which helps to elucidate answers to these questions using model output from our lab.

## Initial Progress

### Gridding Data

These data are in XYZ point files, which I need to convert to rasters. I implement a prototype in Python/GDAL [here](notebooks/Grid + Visualize.ipynb). 

### Static Visualization

For a sanity check I'm creating a static viz of just body temperatures. 

![notebooks/testfigure.png]
