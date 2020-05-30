# WeatherPy

## Project Overview

This project uses Python and the OpenWeatherMap API to analyze trends in weather patterns using the data of 500+ cities around the globe. The code randomly selects over 500 cities at varying distances from the equator and uses matplotlib to create scatter plots that showcase the following relationships:

- Temperature (F) vs. Latitude 
- Humidity (%) vs. Latitude 
- Cloudiness (%) vs. Latitude 
- Wind Speed (mph) vs. Latitude

Some Conclusions from this analysis:
1. The cities with the highest maximum temperatures do not seem to fall exactly ON the equator as I would've expected, but rather are located just below and just above the equator. The cities located right at 0 latitude dip a little bit in temperture. 

2. The trend observed here with regard to humidity I also found to be unexpected. I would've guessed that cities along the equator had a higher percentage of humidity, but the scatter plot indicates that cities between 40 and 80 degrees latitude have a much higher percentage of humidity overall. 

3. The scatter plot with regard to Wind Speed indicates that the wind gets stronger as we move further from the equator. This trend does align with what I would've anticipated.

## Technologies Used

- Python
- Pandas
- NumPy
- OpenWeatherMap API
- GET / requests
- JSON 
- Matplotlib
