# ArcGISPro-Modelbuilder-Automated-utility-network-generation-network-analysis
Inputs:
- buildings
- streets
- heat source
First steps:
- Feature to Point -> centroids of buildings
- create dataset -> add streets -> create network dataset -> build
- create Closest Facility Layer -> add Facility (Heat Source) -> add Incidents (Buildings_Centroids)
- solve Closest Facility -> export first solution (first incident closest to the facility based on lenght) to new Solution Layer
Next steps:
- automate
