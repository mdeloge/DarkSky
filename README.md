# DarkSky Synchronization code
Fetching and parsing weather data from DarkSky.net for use in energymonitoring projects. 

### Initialization
This repository mainly uses Jupyter Notebooks as code containers due to its easy development environment for Python. After cloning this repository startup a notebook by running
   jupyter notebook
and you'll be able to start developing

### Used packages
tqdm  
pandas  
numpy  
urllib2  
requests  
geopy  
json  

# Contained files
### Basic_setup.ipynb
This Jupyter Notebook contains the most basic code to fetch and store weather data using the DarkSky API. Three functions are defined:
   url_builder: Builds a list of url's used in API calls for the DarkSky API
   f_t_c: Fahrenheit to Celsius convertor
   fetch_and_store_json: Fetches the JSON data for a specified fully formatted DarkSky url and stores this data plainly as daily JSON files locally. From hereonafter these files will be used, this reduces the amount of API calls (DarkSky's free tier is limited to 1000 calls per day)



# Powered by the DarkSky API --> darksky.net