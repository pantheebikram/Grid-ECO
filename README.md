# Grid-ECO

This repository contains test cases for **Grid-ECO (Grid Aware Electric Vehicle Charging Stations Placement Optimizer)**.

Currently, the repository includes two test cases for the city of **Seattle**:
- **Downtown feeder**
- **Residential neighborhood feeder**

## Input Data

The input data are provided as CSV files. Each row represents a candidate EV charging station location, and the columns are defined as follows:

- **StationName**: Unique identifier for the candidate charging station  
- **PoleID**: Utility pole identifier, mapped to the corresponding distribution grid node (bus)  
- **CensusBlockID**: Identifier for the census block associated with the location  
- **Node**: Distribution grid bus name  
- **MinParkCapacity**: Minimum parking capacity available at the census block  
- **MaxParkCapacity**: Maximum parking capacity available at the census block  
- **CensusBlockDemand**: Estimated EV charging demand derived from census data  
- **LandCost**: Cost associated with land acquisition for installing charging infrastructure  
- **Lat**: Latitude of the location  
- **Long**: Longitude of the location  
