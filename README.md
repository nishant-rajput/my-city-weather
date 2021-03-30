# Steps To edit, to display your city weather:

1. Head to Open Weather to [Sign up](https://home.openweathermap.org/users/sign_up)
2. Head [here](https://home.openweathermap.org/api_keys) to find your api-key.
3. Download this [json file](http://bulk.openweathermap.org/sample/) and search you city name in it to find your City ID.
4. Open [Weather.js](weather.js)
5. Head to line with code:
```
fetch('https://api.openweathermap.org/data/2.5/weather?id=1261481&appid=d19b217fed0cd976b0612b2f0c323503')
```
5. Edit the below command, by adding your api-key and city-id and replace above line from the code with it.
```
fetch('https://api.openweathermap.org/data/2.5/weather?id= CITY-ID &appid= API-KEY ')
```
