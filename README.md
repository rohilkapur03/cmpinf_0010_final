# cmpinf_0010_final


Metric for Determining Best Neighborhood: Amenities Score

Submetric 1: Entertainment 
  - proximity to parks, recreation, museum, theaters
  - data set for parks & recreations: [https://data.wprdc.org/dataset/parks](https://data.wprdc.org/dataset/allegheny-county-park-features)
  - data set for museums & theaters: https://data.wprdc.org/dataset/allegheny-county-assets 
Submetric 2: Education
  - proximity to schools, libraries, educational institutions
  - data set for public instituions: https://data.wprdc.org/dataset/pittsburgh-public-school-locations
Submetric 3: Commerce
  - proximity to shopping centers, restaruants, job oppurunties
  - data set: https://data.wprdc.org/dataset/allegheny-county-assets
  - 

Pre-Process Data: 
- utilize pandas to import CSV files as dataframes 
- merge the dataframes based on columns of choice 
- remove null / missing values and columns that are unnecessary 
- geocode using google maps libraries (longitude and latitude of each location)


Process / Analyze Data:
- calculate proximity scores for each neighborhood based on geocode 
- normalize the proximity scores 
- propose weightage for each of the submetrics (33%, 33%, 33%) based on importance 
- obtain a single amenities score based on the submetric normalized proximity curves 
- rank the amenities score to find the best neighborhood 


