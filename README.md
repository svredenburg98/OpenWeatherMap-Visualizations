# python-api-challenge

#WeatherPY

Using the Open Weather Map API, I randomly generated a list of cities using a random number generator to create coordinates and citipy to get cities based on those coordinates. I had to generate 1300 coordinates to get a list of over 500 cities after deleting all duplicates. I then found weather data for all the cities and put it into a new data frame which I then used with the matplotlib library to create some visualizations on various weather information. 

According to the charts, temperature tends to increase as cities get closer to the equator from either direction, Humidity and cloudiness have little correlation with latitude. Cloudiness also seemed not to correlate with latitude but also had interesting clusters which appear to be based on how data is input.

#VacationPY

Using the weather data from the previous file, I reduced the dataset down to cities with the ideal weather for me- temperatures between 60F and 70F, and low wind speed. I ended up with about 40 coordinates which I then ran against the google places API to find hotels nearby. After dropping all rows with null values, I ended up with about 20 potential vacation destinations, an unusual amount of which were in Alaska.
