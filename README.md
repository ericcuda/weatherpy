# PYBER

PROJECT NAME: What's the Weather Like?  
DESCRIPTION: Homework #6  Data Analytics Boot Camp  
DUE: 06MAR2019
PROGRAMMER:  Eric Staveley  MWSa Session  
SUMMARY:    The student is to write an application that accesses two data sources
            and generate output to the terminal and filesystem.  

An API key is required for OpenWeatherMap access

Input:
Tha application will use citypy module to determine cities from 1500 random longitude
and latitude determinations.

Thos cities will then be used in 500+ API calls to OpenWeatherMap to retrieve weather infomration,
and will be displayed to the terminal.  Files will also be saved to the filesystem:
a data csv file and various .png files representing data vs latitude.

 Files located at the root level of the github repo url:

* `README.md` (this file).      - Describes project
* `WaetherPy.ipynb`             - jupyter notebook file.  Constains data summary in MarkDown at top of file


Ouput files will be generated at root level of this github repo url:
* `output_data\city_weather.csv` (a data dump of final city weather information)
* `output_data\LatitudeByWindSpeedScatterPlotWorldCities.png` (scatter chart)
* `output_data\LatitudeByMaxTemperatureScatterPlotWorldCities.png` (scatter chart)
* `output_data\LatitudeByHumidityScatterPlotWorldCities.png` (scatter chart)
* `output_data\LatitudeByCloudinessScatterPlotWorldCities.png` (scatter chart)

WeatherPy.ipynb should be opened with jupyter notebook.

## Weather Data Overview Analysis (also included in the ipynb file)

As observed from the Latitude vs Wind Spped scatter plot, it appears that there is a slightly higher occurrence of winds over 15mph in the northern hemisphere, than found in the cities in the southern hemisphere.

As observed from the latitude v Cloudiness scatter plt, it appears that there are interesting comon bands of "readings" at the 0%, 20%, 40%, ~75%, making it appear that these readings are somewhat subjective, and approximated by the measurement method.

As observed from the Latitude vs Max Temperature scatter plot, it is obvious that the max temperature increases as one approaches the equator, and at the time of this data mining (March in Austin, TX), the southern hemisphere is experiencing warmer temperatures, which makes sense, since it is "summer" below the equator at the present time.

## TABLE OF CONTENTS:
None

## INSTALLATION:
None

## USAGE:
WeatherPy.ipynb should be opened with jupyter notebook

## CONTRIBUTING:
n/a

## CREDITS:
n/a

## LICENSE:
n/a
