This is the repository for Ben Bagby's Module 6 Challenge

  WeatherPy.ipynb
  
  - This file pulls random cities weather data from around the world based a geographical coordinates (Latitude, Longitude)
  - Plots are created to find relationship patterns of Latitude vs. (Temperature, Humidity, Cloudiness, and Wind Speed)
  - Data pulled is based off of current date and time (10/29/23, 2pm CT)

  VactationPy.ipynb
  
  - This file plots the coordinates of the random cities on a map and filters through ideal critereia of the data points
  - A for loop is constructed to make an API request based off of the ideal criteria to find the nearest hotel in queried city
  - The hotels are added to the ideal dataframe and plotted on a map

  cities_csv
    - Random city data is stored in this csv file

  Note: 
   - The temperature criteria was widened due to lack of returned data
   - api_keys.py was accidentally pushed without .gitignore due to spelling error
