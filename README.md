# python-api-challenge
Python API Homework

<b>INSTRUCTIONS FOR THE TA</b>

<b>INPUT DATA</b>

The <b>"input_data"</b> directory contains 1 file:
  * Cities.csv

This file is <b>OPTIONAL</b> input for the weather code file and can be used instead of calling the OpenWeatherMap API. So, remove this file if you are testing the OpenWeatherMap API.  When run, the weather code file will create a new Cities.csv file in the "output_data" directory or, if it already exists, the existing file will be over-written.

However, the Cities.csv file is <b>REQUIRED</b> for the vacation code to run. So, if you remove this file to run the weather code, please replace it before you run the vacation code.

------------------------------------

<b>OUTPUT DATA</b>

The <b>"output_data"</b> directory contains several files:

  <b>CSV Files:</b>
  * Cities.csv - output file for weather code file and will be over-written if it exists on each run
  
  <b>Scatter Plot Images:</b>
  * Cities_LatvClouds.png - Latitude versus Clouds
  * Cities_LatvHum.png - Latitude versus Humidity
  * Cities_LatvTemp.png - Latitude versus Temperature
  * Cities_LatvWind.png - Latitude versus Wind

  * NH_CloudsvLat.png - Northern Hemisphere Latitude versus Cloudiness
  * SH_CloudsvLat.png - Southern Hemisphere Latitude versus Cloudiness

  * NH_HumidvLat.png - Northern Hemisphere Latitude versus Humidity
  * SH_HumidvLat.png - Southern Hemisphere Latitude versus Humidity

  * NH_TempvLat.png - Northern Hemisphere Latitude versus Temperature
  * SH_TempvLat.png - Southern Hemisphere Latitude versus Temperature

  * NH_WindvLat.png - Northern Hemisphere Latitude versus Windiness
  * SH_WindvLat.png  - Southern Hemisphere Latitude versus Windiness

The image and csv files in the "output_data" directory will be over-written each time the weather code runs.
