# Weather-Journal Application 

## Overview
This project uses both end-user input (zip code and user's feelings) - 
### Behind the scenes : 
* Make a get request to OpenWeatherMap API to get the location's temperature
* Post a data object to the Express Server 
* This data object is the end-user's input which returns the specific OpenWeatherMap API data with a dynamically-generated date 
* Get data from the Express Server and update the UI accordingly

#### Instructions
- Get Udacity-provided project code 
- Locally make usre NodeJS is installed (run 'npm i' from your terminal at the top level project directory to install via the Command Line)  
- Enter a (US-based) zip code in form of '{zipcode},{country code}', e.g., '94712,us' then click Generate button
