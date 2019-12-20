# Weather-Journal App Project

## Overview
This project uses both end-user input (zip code and user's feelings) 
Process: 
1) Make a get request to OpenWeatherMap API to get the location's temperature
2) Post a data object to the Express Server. This data object is user input; returned OpenWeatherMap API data and a dynamically-generated date.
3) Get data from the Express Server and update the UI accordingly.

## Instructions
a) Get Udacity-provided project code 
b) Locally NodeJS is installed then run 'npm i' from your terminal at the top level project directory.
c) Enter a (US-based) zip code in form of '{zipcode},{country code}', e.g., '94712,us' then click Generate button