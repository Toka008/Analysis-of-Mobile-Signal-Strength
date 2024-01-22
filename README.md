# Analyzing Mobile Signal Strength and Enhancing Network Performance

## Context
- The speed, capacity, and connection of mobile communication have all improved with the switch from 2G to 5G. But issues like dropped calls and sluggish internet still exist. With a video demonstration and suggestions, a project seeks to remedy these problems.

## Expected Outcomes
- Analyze mobile signal strength data in detail.
- Make extensive use of ExploreAI's vast datasets to examine signal dynamics in detail.
- Investigate using machine learning to forecast the positions of cell towers.
- On the basis of analysis insights, offer recommendations for telco network optimization.
- Arrange mobile towers optimally to improve coverage and minimize interference.
- Strengthen network performance with recommendations based on data.


## Tools Used
- VS Code, or Visual Studio Code
- Python's Jupyter Notebook
- Seaborn, Numpy, Pandas, Matplotlib
- Scipy.fft, JSON, Random, Requests
- Pyspark, Statsmodels.api, Contextily, Geopandas
- Plotly.express, 4..graph_objects
- Folium, Time, and Math
- Kepler.gl, Streamlit

## Scope 
- ExploreAI's exclusive tool was used to analyze mobile signal strength data from the Johannesburg to Cape Town drive, providing valuable insights for network performance enhancement.
![data_points_1](https://github.com/Toka008/git-primer/assets/63381061/fffd29a6-822c-4fff-9412-b85fce08e2c4)
- The accompanying map highlights important locations from the drive between Johannesburg and Cape Town by using Kepler.gl to graphically represent the route and signal dynamics.

## Geospartial Analysis
- The study makes the considerable impact that tower clustering, cell tower distance, and mobile device proximity have on signal quality. Locations with subpar signal quality because of tower clustering or device placement at the tower edge were identified by a geospatial analysis.
![tower_position_2](https://github.com/Toka008/git-primer/assets/63381061/bdca6249-8f73-485a-9e51-30715566a980)
- The map shows specific locations along the authorized drive in Cape Town. The clustering of cell towers at Location A results in less-than-ideal signal quality in the surrounding area. On the other hand, Location B's low signal strength is explained by its great distance from the closest cell towers.

## Population Density
- According to the investigation, Johannesburg's signal quality is often worse than that of other less populous towns and cities along the route, especially in heavily populated areas.
![population_density](https://github.com/Toka008/git-primer/assets/63381061/431ef69a-db5a-4c70-accc-de4d27f354bb)
- The legend next to the image indicates that the color of the squares serves as a visual representation of population density. The map shows the population density of cities in South Africa.

## Physical Obstruction
- Our observations led us to conclude that the signal quality is impacted by the proximity of large structures.
![physical_obstruction](https://github.com/Toka008/git-primer/assets/63381061/7a065154-32cd-444f-b295-af2e2749937e)
- The Randburg, Johannesburg, signal quality maps are displayed with yellow symbols for larger structures and blue symbols for smaller ones. The signal gets stronger farther away but gets weaker closer to big structures. Because there are fewer people living there and fewer buildings, Beaufort West enjoys higher signal quality. Removing physical obstacles is essential to maximize the strength of your mobile signal.

## Solution Approach
![solution_approach](https://github.com/Toka008/git-primer/assets/63381061/958682f9-526e-488f-af80-02d2cf461e4a)
- The ConnectXplorer App offers a complete network management solution with the integration of the Cell Tower Locator Engine and Network Optimization Engine. While the Network Optimization Engine controls data flow, increases internet speed, and maximizes the use of network resources, the Cell Tower Locator Engine locates the sources of signals. The intuitive app makes it simple to monitor networks and makes wise decisions.

## Data Pipeline
![data_pipeline](https://github.com/Toka008/git-primer/assets/63381061/6c53c453-98f9-46b9-b500-a1011b9afa24)
- Our process employs an EC2 instance and Streamlit for smooth application deployment, Python for data pre-processing, and secure S3 bucket data storage.

# Limitations
- The study's shortcomings include its unreliability due to insufficient data on cell tower height, antenna type, frequency, direction of signal propagation, and geographic dynamicity

## Recommendations
- The research indicates that monitoring the frequency data that cell towers communicate may improve network efficiency since it raises the possibility of receiving disruptive messages.
- The plan recommends improving signal strength, minimizing interference, and strategically spacing cell towers to optimize network performance.
- During the data gathering process, use real-time timestamp recording to capture dynamic datasets and enhance network strategy for efficient Time Series Analysis.

## Conclusion
- The distance between cell towers, population density, and physical obstructions are among the main factors affecting signal quality, as shown by ExploreAI's analysis of mobile signal strength data from Johannesburg to Cape Town.
- Using a thorough solution approach and data pipeline procedure, ExploreAI's unique tool was used to analyze and optimize network performance with an emphasis on tower clustering, population density, and building sizes.
- The study ended with suggestions for strengthening mobile signal strength, optimizing network performance, and refining algorithms, as well as providing insightful information for network design and improvement

## Acknowledgements
Special thanks to the project team members for their contributions:
- Adekemi Folarin
- Ajirioghene Oguh
- Aldo Sauls
- Monde Nkuna
- Samson Ayankunle


