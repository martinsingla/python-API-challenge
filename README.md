# python-API-challenge
Data analytics challenge using APIs interactions with Python. Part of the Data Analytics Bootcamp course by Tecnoógico de Monterrey / Trinity Education

Part 1 - Weather Analysis

In this first part we aim to prove if proximity to the Earth's Equator is correlated with higher temperatures. We use CitiPy module to create a random sample of over 2 thousand cities across the globe and following that we use OpenWeatherMap API to retreive meteorological data from those cities. Finally we run some regression analysis and build some scatterplots to see and test the relationship between meteorological variables and Latitude. Only Linear regression models are tested, other non-linear alternatives are suggested.

Part 2 - Vacations Analysis

In this second part we take the global weather database developed in Part 1, and create a global heatmap of observed humidity percentages by city using Gmap module. Following that we filter and narrow down the dataset to 10~20 cities based on our optimal weather conditions for a nice vacation trip (chill temperature, low humidity, etc.). We then look for hotels in those cities using Google Places API and plot them using Gmaps.
