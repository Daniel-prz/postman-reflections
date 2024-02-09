# postman-reflections

# Day 1

1. Charizard

![charizard](<Screenshot 2024-02-05 214935.png>)

name: charizard  
height:17  
moves: mega-punch, fire-punch, thunder-punch  
abilities: blaze, solar-power

2. Mew

![Mew](<Screenshot 2024-02-05 215227.png>)

name: mew  
height: 4  
moves: pound, mega-punch, pay-day  
abilities: synchronize

3. Hitmonlee

![Hitmonlee](<Screenshot 2024-02-05 220026.png>)

name: hitmonlee  
height: 15  
moves: mega-punch, swords-dance, double-kick  
abilities: limber, reckless, unburden

# Day 2

![Weather Data, New York](<Screenshot 2024-02-06 222430.png>)

Request URL: https://api.meteomatics.com/2024-02-06T10:00:00.000-05:00--2024-02-06T20:00:00.000-05:00:PT2H/t_2m:F/40.6763399,-73.8745196/json?model=mix  
Location: New York, 11208
Date: 2024-02-06
Parameters: 2m(meters), F(degrees fahrenheit)

Response (Zulu Time, Temperature Fahrenheit):  
T15:00:00Z, 34.5 F  
T17:00:00Z, 38.8 F  
T19:00:00Z, 40.9 F

# Day 3

# API Collections

![Weather API Request](<Screenshot 2024-02-07 214313.png>)

Weather API Collection made

Added weatherAPIkey variable

Made weatherAPIkey variable value into my WeatherAPI Key

Made request using Weather API Collection as active environment

Used weatherAPIKey variable to call Weather API Key

weatherAPIKey variable allowed easy access to API
key, as long as request was made in proper active environment with API key as variable

# Day 4

# GitHub API Interaction

![User information accessed with GET request](<Screenshot 2024-02-08 214751.png>)

GitHub API Environment created and saved  
patGitHub variable created inside environment  
patGitHub value set to generated classic personal access token  
GitHub API set as active environment  
GitHub Post request Collection created and saved  
baseURL variable created inside and saved  
baseURL value set to github api url  
GitHub Post Request Authorization set to Bearer Token  
Token set to patGitHub  
Made New Get Request  
({baseURL})user
Request sent
Response received as user information

![Repository created with POST request](<Screenshot 2024-02-08 215555.png>)

Set request to POST  
({baseURL})user/repos  
create repo with name as JSON object in body tab  
Send POST request  
201 Message code signifies request successfully fulfilled  
Checked GitHub to see created repository
