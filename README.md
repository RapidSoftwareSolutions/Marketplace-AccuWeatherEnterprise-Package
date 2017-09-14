[![](https://scdn.rapidapi.com/RapidAPI_banner.png)](https://rapidapi.com/package/AccuWeatherEnterprise/functions?utm_source=RapidAPIGitHub_AccuWeatherEnterpriseFunctions&utm_medium=button&utm_content=RapidAPI_GitHub)

# AccuWeatherEnterprise Package
AccuWeather provides hourly and Minute by Minute™ forecasts with Superior Accuracy™ for any longitude/latitude on Earth, with customized content and engaging video presentations available on smart phones, tablets, free wired and mobile Internet sites, connected TVs, and Internet appliances, as well as via radio, television, and newspapers.
* Domain: [AccuWeatherEnterprise](http://accuweather.com/)
* Credentials: apiKey

## How to get credentials: 
0. Contact sales@accuweather.com to receive an API key.


## Custom datatypes: 
 |Datatype|Description|Example
 |--------|-----------|----------
 |Datepicker|String which includes date and time|```2016-05-28 00:00:00```
 |Map|String which includes latitude and longitude coma separated|```50.37, 26.56```
 |List|Simple array|```["123", "sample"]``` 
 |Select|String with predefined values|```sample```
 |Array|Array of objects|```[{"Second name":"123","Age":"12","Photo":"sdf","Draft":"sdfsdf"},{"name":"adi","Second name":"bla","Age":"4","Photo":"asfserwe","Draft":"sdfsdf"}] ```
 

## AccuWeatherEnterprise.getCurrentConditionsByLocationKey
Current Conditions By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| getPhotos  | Select     | Boolean value specifies whether or not to include photos representing the requested location and current condition
| group      | Number     | Integer value (50, 100, or 150) that specifies the number of cities to return

## AccuWeatherEnterprise.get6HoursConditionsByLocationKey
Historical Current Conditions (past 6 hours) By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| getPhotos  | Select     | Boolean value specifies whether or not to include photos representing the requested location and current condition
| group      | Number     | Integer value (50, 100, or 150) that specifies the number of cities to return

## AccuWeatherEnterprise.get24HoursConditionsByLocationKey
Historical Current Conditions (past 24 hours) By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| getPhotos  | Select     | Boolean value specifies whether or not to include photos representing the requested location and current condition
| group      | Number     | Integer value (50, 100, or 150) that specifies the number of cities to return

## AccuWeatherEnterprise.getCurrentConditionsForTopCities
Current Conditions for Top Cities

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| language | Select     | String indicating the language in which to return the resource
| details  | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| getPhotos| Select     | Boolean value specifies whether or not to include photos representing the requested location and current condition
| group    | Number     | Integer value (50, 100, or 150) that specifies the number of cities to return

## AccuWeatherEnterprise.getMinuteForecastByCoordinates
MinuteCast™ Forecasts By Latitude, Longitude

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| coordinates| Map        | Coordinates for the forecast

## AccuWeatherEnterprise.getMinutesForecastByCoordinates
MinuteCast™ Premium Forecasts By Latitude, Longitude

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| coordinates| Map        | Coordinates for the forecast
| minutes    | Select     | Number of minutes to get forecast for
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object

## AccuWeatherEnterprise.getColorFullSpectrum
MinuteCast™ Premium Full Spectrum of Colors

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## AccuWeatherEnterprise.getHoursForecastByLocationKey
Hourly Forecasts By Location Key

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| hours      | Select     | Number of hours to get forecast for
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| metric     | Select     | Boolean value (true or false) that specifies to return the data in either metric (=true) or imperial units 

## AccuWeatherEnterprise.getDailyForecastByLocationKey
Daily Forecasts By Location Key

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| days       | Select     | Number of days to get forecast for
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| metric     | Select     | Boolean value (true or false) that specifies to return the data in either metric (=true) or imperial units 

## AccuWeatherEnterprise.getLocalWeatherByLocationKey
LocalWeather By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object
| getPhotos  | Select     | Boolean value specifies whether or not to include photos representing the requested location and current condition
| metric     | Select     | Boolean value (true or false) that specifies to return the data in either metric (=true) or imperial units 

## AccuWeatherEnterprise.getAlertsByLocationKey
Alerts By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object

## AccuWeatherEnterprise.getCurrentAirQualityByLocationKey
Current Air Quality By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location

## AccuWeatherEnterprise.getPastDayAirQualityByLocationKey
Past Day Air Quality By LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location

## AccuWeatherEnterprise.listDailyIndices
Metadata List of Daily Indices

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getIndiceByIndex
Metadata of a Specific Index

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| indexId | String     | Unique ID used to search for a specific index
| language| Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.listDailyIndicesGroups
Metadata List of Index Groups

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getIndiceByGroupId
Metadata List of Indices in a Specific Group

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| groupId | String     | Unique ID used to search for a specific group
| language| Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getLocationIndicesByIndexId
Daily Indices By LocationKey and IndexId

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| days       | Select     | Days for get indice for
| indexId    | String     | Unique ID used to search for a specific index
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object

## AccuWeatherEnterprise.getLocationIndicesByGroupId
Daily Indices By LocationKey and GroupId

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| days       | Select     | Days for get indice for
| groupId    | String     | Unique ID used to search for a specific group
| language   | Select     | String indicating the language in which to return the resource
| details    | Select     | Boolean value (true or false) that specifies whether or not to include a truncated version of the current conditions object or the full object

## AccuWeatherEnterprise.getWeatherAlarmByLocationKey
DailyWeather Alarms By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| days       | Select     | Days for get indice for
| language   | Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getMonthClimoActualsByLocationKey
Climo Actuals For Month By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm

## AccuWeatherEnterprise.getDayClimoActualsByLocationKey
Climo Actuals For Day By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getRangeClimoActualsByLocationKey
Climo Actuals For date range By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| start      | DatePicker | Date in format yyyy/mm/dd
| end        | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getMonthClimoRecordsByLocationKey
Climo Records For Month By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm

## AccuWeatherEnterprise.getDayClimoRecordsByLocationKey
Climo Records For Day By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getRangeClimoRecordsByLocationKey
Climo Records For date range By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| start      | DatePicker | Date in format yyyy/mm/dd
| end        | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getMonthClimoNormalsByLocationKey
Climo normals For Month By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm

## AccuWeatherEnterprise.getDayClimoNormalsByLocationKey
Climo normals For Day By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getRangeClimoNormalsByLocationKey
Climo normals For date range By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| start      | DatePicker | Date in format yyyy/mm/dd
| end        | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getMonthClimoSummaryByLocationKey
Climo summary For Month By Location Key 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| date       | DatePicker | Date in format yyyy/mm

## AccuWeatherEnterprise.listCyclones
Active Tropical Cyclones 

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| basinId| Select     | Unique id used to identify a basin (NP, SP, NI, SI, AL, EP )

## AccuWeatherEnterprise.getSingleCyclone
Get cyclone information

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| basinId  | Select     | Unique id used to identify a basin (NP, SP, NI, SI, AL, EP )
| cycloneId| Number     | Numeric id of the tropical cyclone
| year     | DatePicker | Date in format yyyy

## AccuWeatherEnterprise.getSingleCyclonePosition
Get cyclone current position

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| basinId  | Select     | Unique id used to identify a basin (NP, SP, NI, SI, AL, EP )
| cycloneId| Number     | Numeric id of the tropical cyclone
| year     | DatePicker | Date in format yyyy

## AccuWeatherEnterprise.listSingleCyclonePositions
List cyclone current positions

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| basinId  | Select     | Unique id used to identify a basin (NP, SP, NI, SI, AL, EP )
| cycloneId| Number     | Numeric id of the tropical cyclone
| year     | DatePicker | Date in format yyyy

## AccuWeatherEnterprise.getSingleCycloneForecast
Get cyclone forecast

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| basinId  | Select     | Unique id used to identify a basin (NP, SP, NI, SI, AL, EP )
| cycloneId| Number     | Numeric id of the tropical cyclone
| year     | DatePicker | Date in format yyyy

## AccuWeatherEnterprise.getTridalForecastByLocationKey
Returns an array of daily tidal forecasts for every tidal station that falls within the area defined by the given locationKey. 

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| days       | Select     | Number of days to get forecast for
| language   | Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getAstronomyByLocationKey
Astronomy By LocationKey and Date Range

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| start      | DatePicker | Date in format yyyy/mm/dd
| end        | DatePicker | Date in format yyyy/mm/dd

## AccuWeatherEnterprise.getImagesByLocationKey
Radar and Satellite Images by LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| resolution | Select     | Available resolutions: 480x480, 640x480, 1024x1024

## AccuWeatherEnterprise.listLanguages
List all Languages

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## AccuWeatherEnterprise.listTranslationGroups
List of Available Translation Groups

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## AccuWeatherEnterprise.getSingleGroupTranslations
List of Translations for a Specific Group

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| groupId | String     | Unique ID of a translation group
| language| Select     | String indicating the language in which to return the resource

## AccuWeatherEnterprise.getDeepLinksByLocationKey
Deep Links by LocationKey

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| locationKey| String     | Unique ID used to search for a specific location
| language   | Select     | String indicating the language in which to return the resource
| types      | List       | Array of data types to include in the response. Possible values are: Alerts, CurrentConditions, DailyForecasts, ExtendedForecasts, Home, HourlyForecasts, MinuteForecasts, MonthForecasts, QuarterlyForecastsMorning, QuarterlyForecastsAfternoon, QuarterlyForecastsEvening, QuarterlyForecastsOvernight, Radar, Satellite, Tides.
| dayNumber  | Number     | Desired start day of the forecast.
| hourNumber | Number     | Desired start hour of the forecast (0-23). This number should not exceed 23.
| metric     | Select     | Boolean value (true or false) that specifies to return the data in either metric (=true) or imperial units 

