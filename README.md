# Airbnb Data Analysis

## Project Motivation
As part of a nanodegree at Udacity, this jupyter notebook explores airbnbs in Seattle with a focus on trying to answer questions that might help a person that wants to start an airbnb business.
## Abstract
This project answers thre questions
* Which would be the best neighborhood to list an airbnb?
  * A table is built as a tool that will help decide which beighborhood is the best option.
* How much pricing varies per month?
  * It is clear that weather plays a big role, prices are the highest(7% above the yearly median) from June to August due to nice weather conditions and consequently higher number of activities available after that, prices drop as winter comes from October to February, they might not be dropping as much on November to December because of holidays, but they go down on -6% on average on January.
* Does being a super-host makes the difference?
  * Yes, superhost's listings are more successfull on average than non-superhost's listings.

## Data Used
* [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data)
* [City Clerk Neighborhoods](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::city-clerk-neighborhoods/about)
* [Home sales in King County](https://geodacenter.github.io/data-and-lab/KingCounty-HouseSales2015/)
## Libraries Used
* **pandas** for data manipulation and analysis
* **matplotlib.pyplot** for graphs
* **geopandas** for geospatial analysis
* **cmd** just for formated printing of columns
* **seaborn** for grapghs
* **random**
* **scipy.stats mannwhitneyu** for Mann Whitney U test

## Files
* **airbnbs_data**
  * **link_to_download_data.txt** link to download kaggle's data on airbnbs in Seattle
* **shape_files**
  * **kingcounty** House sales information of King County
  * **City_Clerk_Neighborhoods.geojson** Shapes for Seattle's neighborhoods
* **Seattle Airbnb Data Analysis.ipynb** Jupyter Notebook 
