# cmpinf_0010_final


Metric for Determining Best Neighborhood: Neighborhood Atmosphere Score

Submetric 1: Tree population 
  - amount of trees and greenery per neighborhood.
  - data set for trees and greenery: 
  https://data.wprdc.org/dataset/city-trees

Submetric 2: Education
  - proximity to schools, libraries, educational institutions
  - data set for public instituions: https://data.wprdc.org/dataset/pittsburgh-public-school-locations


Submetric 3: Traffic Data
  - level of foot traffic measuring safety in neighborhoods.
  - data set: https://data.wprdc.org/dataset/traffic-count-data-city-of-pittsburgh



Pre-Process Data: 
- utilize pandas to import CSV files as dataframes 
- merge the dataframes based on columns of choice 
- remove null / missing values and columns that are unnecessary 
- geocode using google maps libraries (longitude and latitude of each location)


Process / Analyze Data:
- calculate proximity scores for each neighborhood based on geocode 
- rank the amenities score to find the best neighborhood 


