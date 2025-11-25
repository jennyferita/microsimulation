Welcome to out Github repository project

This repository hosts the full workflow used to simulate mobility patterns, generate origin–destination demand, 
evaluate different current scenarios, and compute vehicular emissions using SUMO and Python. The project integrates microsimulation, 
GIS-based preprocessing, edge-level analytics, and multimodal performance indicators for the Distrito Tec study area in Monterrey. 
All code, configurations, and supporting resources are provided for reproducibility and further research.

The workflow is organized into six main steps. First, we start from demographic information, analyzing official census data from government sources. 
Second, we construct the origin–destination (OD) matrices that describe how people move between different zones. 
Third, we apply a multi-modal transportation model to the OD matrices, creating a probabilistic 3D matrix that captures trips by activity, mode, and time. 
Fourth, we use this structure to generate individual activities and trip flows. In this step, the input file for the SAGA model is created. 
Fifth, a customized SAGA implementation uses this input to generate detailed trip itineraries. 
Finally, in the sixth step, these trips are used as input for microscopic traffic modeling and simulation in SUMO.
