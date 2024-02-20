# WeatherPy

## Overview
The WeatherPy folder contains two Jupyter Notebook files: WeatherPy.ipynb and VacationPy.ipynb. WeatherPy.ipynb fetches weather data for various cities using the OpenWeather API and performs data analysis. VacationPy.ipynb utilizes the output from WeatherPy.ipynb to generate analysis based on certain parameters and utilizes the Geoapify API to find the closest hotels to filtered cities.

## Contents
- **WeatherPy.ipynb:** Jupyter Notebook file containing the code for fetching weather data and conducting analysis using the OpenWeather API.
- **VacationPy.ipynb:** Jupyter Notebook file containing the code for generating analysis based on weather data and using the Geoapify API to find nearby hotels.
- **README.md:** Readme file providing instructions and an overview of the WeatherPy and VacationPy analyses.

## Instructions
1. **Running the WeatherPy Analysis:**
   - Open the WeatherPy.ipynb notebook in Jupyter Notebook or JupyterLab.
   - Ensure that you have installed the required dependencies listed in the notebook.
   - Run the cells sequentially to execute the code and generate the analysis.
   - WeatherPy.ipynb will fetch weather data for various cities using the OpenWeather API and perform data analysis, including visualizations of weather patterns.

2. **Running the VacationPy Analysis:**
   - After completing the WeatherPy analysis, open the VacationPy.ipynb notebook.
   - Ensure that you have installed the required dependencies listed in the notebook.
   - Run the cells sequentially to execute the code and generate the analysis.
   - VacationPy.ipynb will utilize the weather data obtained from WeatherPy and filter cities based on desired parameters. It will then use the Geoapify API to find nearby hotels for the filtered cities.

3. **API Keys:**
   - To run the code, ensure that you have API keys for the OpenWeather API and the Geoapify API.
   - Create an 'api_keys.py' file in the WeatherPy Folder
   - Add your OpenWeather API key to the `api_keys.py` file located in the WeatherPy folder.
   - Ensure that you have the Geoapify API key accessible for use in the VacationPy analysis.

## Dependencies
- pandas
- numpy
- requests
- matplotlib
- scipy

## Additional Notes
- Ensure that you have added api_keys.py as a config file for the OpenWeather API and the Geoapify API before running the analysis.
- You will need to place the api key in this api_keys.py once obtained from the website.