# SteamQuest
A web app to analyze and predict steam community market prices.

## Setting up the environment
```
cd App
npm install
```
 - Create a .env file and add the following variables:
 
 | Variable name      | Description                                                                |
 | ------------------ | -------------------------------------------------------------------------- |
 | MONGO_URL          | Your MongoDB connection string                                             |
 | STEAM_API_KEY      | Get your own API KEY from [here](https://steamcommunity.com/dev/apikey)    |
 | REALM              | your base URL (```http://localhost:8080/``` if you are running it locally) |

- **Optional:** Clone [this](https://github.com/Nightmare99/Vapourizer) repo for fetching the steam item price histories. 

## Start the server
```npm start``` 
Server starts in port 8080 by default. Have fun.

## Team

- Vishal
- Ashwin
- Shyam
- Robin

## Deployed at

https://steamq.herokuapp.com
