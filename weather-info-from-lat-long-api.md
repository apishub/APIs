# [Weather Info from Lat Long API](https://apishub.com/marya-fatima/weather-info-from-lat-long-api)

Get weather info from latitude and longitude

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| lat | double | required | Latitude of the place |
| long | double | required | Longitude of the place |



### Example Response

```json
{
   "latitude":24.8607,
   "longitude":67.0011,
   "timezone":"Asia/Karachi",
   "currently":{
      "time":1528112791,
      "summary":"Humid",
      "icon":"clear-day",
      "precipIntensity":0,
      "precipProbability":0,
      "temperature":92.2,
      "apparentTemperature":104.73,
      "dewPoint":75.92,
      "humidity":0.59,
      "pressure":999.43,
      "windSpeed":17.61,
      "windGust":27.45,
      "windBearing":261,
      "cloudCover":0.09,
      "uvIndex":2,
      "visibility":3.11,
      "ozone":289.01
   },
   "hourly":{
      "summary":"Humid throughout the day.",
      "icon":"clear-day",
      "data":[
         {
            "time":1528110000,
            "summary":"Humid",
            "icon":"clear-day",
            "precipIntensity":0,
            "precipProbability":0,
            "temperature":92.92,
            "apparentTemperature":105.25,
            "dewPoint":75.59,
            "humidity":0.57,
            "pressure":999.57,
            "windSpeed":17.82,
            "windGust":27.51,
            "windBearing":266,
            "cloudCover":0.1,
            "uvIndex":3,
            "visibility":3.11,
            "ozone":289.05
         }
      ]
   },
   "daily":{
      "summary":"No precipitation throughout the week, with high temperatures falling to 91°F on Saturday.",
      "icon":"clear-day",
      "data":[
         {
            "time":1528052400,
            "summary":"Humid throughout the day and breezy until afternoon.",
            "icon":"wind",
            "sunriseTime":1528073018,
            "sunsetTime":1528121998,
            "moonPhase":0.68,
            "precipIntensity":0.0001,
            "precipIntensityMax":0.0005,
            "precipIntensityMaxTime":1528063200,
            "precipProbability":0.06,
            "precipType":"rain",
            "temperatureHigh":94.49,
            "temperatureHighTime":1528102800,
            "temperatureLow":84.93,
            "temperatureLowTime":1528156800,
            "apparentTemperatureHigh":107.31,
            "apparentTemperatureHighTime":1528106400,
            "apparentTemperatureLow":97.73,
            "apparentTemperatureLowTime":1528156800,
            "dewPoint":76.21,
            "humidity":0.69,
            "pressure":1001.37,
            "windSpeed":17.6,
            "windGust":27.89,
            "windGustTime":1528092000,
            "windBearing":256,
            "cloudCover":0.2,
            "uvIndex":12,
            "uvIndexTime":1528095600,
            "visibility":3.37,
            "ozone":288.99,
            "temperatureMin":84.22,
            "temperatureMinTime":1528066800,
            "temperatureMax":94.49,
            "temperatureMaxTime":1528102800,
            "apparentTemperatureMin":93.18,
            "apparentTemperatureMinTime":1528074000,
            "apparentTemperatureMax":107.31,
            "apparentTemperatureMaxTime":1528106400
         }
      ]
   },
   "flags":{
      "sources":[
         "isd",
         "cmc",
         "gfs",
         "madis"
      ],
      "isd-stations":[
         "417420-99999",
         "417640-99999",
         "417650-99999",
         "417800-99999",
         "417810-99999",
         "417820-99999",
         "417850-99999"
      ],
      "units":"us"
   },
   "offset":5
}
```
### Demo
[Try here](https://apishub.com/marya-fatima/weather-info-from-lat-long-api#try-now)
