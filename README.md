## oil_well_selection
The task is to find the best place for a new well for OilyGiant mining company.

Steps to choose the location:
- Collect the oil well parameters in the selected region: oil quality and volume of reserves;
- Build a model for predicting the volume of reserves in the new wells;
- Pick the oil wells with the highest estimated values;
- Pick the region with the highest total profit for the selected oil wells.

We have data on oil samples from three regions. Parameters of each oil well in the region are already known. In the project I will build a model that will help to pick the region with the highest profit margin. And analyze potential profit and risks using the Bootstrapping technique.

## Data description
Geological exploration data for the 3 regions are sorted in the files
- geo_data_0.csv 
- geo_data_1.csv 
- geo_data_2.csv 

Features:
- id - Unique oil well identifier
- f0, f1, f2 - 3 features of points (their specific meaning is unimportant, but the features themselves are significant)
- product — volume of reserves in the oil well (thousand barrels)

