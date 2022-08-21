# go-temp

API to get the temperature from a city.

## Requirements
* Account on https://openweathermap.org/
* Get an Api Key an put it in the .apiConfig file

## How to use the Api
### Request
GET to `localhost:8080/weather/?city=desired_city`

### Response
```json
{
    "Name":"desired_city",
    "main":{
        "temp":000.00
    }
}
```
