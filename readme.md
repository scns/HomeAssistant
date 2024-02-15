# Handige Homeassistant scripts en dashboards


# Dashboards

## Weather

### Windspeed and Direction

![windspeed and direction](/Dashboards/LoveLace/Weather/Windspeed_and_direction.png "windspeed and direction")

1. Take a screenshot of the satellite view of your house (or location of the weather station) and save to the following directory of your HA config: `config/www/'
2. replace <file.jpg> in the config below with the name of your image
3. You'll need to install the [compass-card](https://github.com/tomvanswam/compass-card)
4. and of cource change the sensors

### Overview Weather Forecast

![overview weather forecast](/Dashboards/LoveLace/Weather/Overview_Weather_forecast.png "overview weather forecast")

1. you need to install the [clock-weather-card](https://github.com/pkissling/clock-weather-card)
2. you need to install the [apexcharts-card](https://github.com/RomRider/apexcharts-card)
3. you need to install the [Home Assistant Neerlas app](https://github.com/aex351/home-assistant-neerslag-app)
4. and of cource change the sensors

### Complete weather dashboard

This is the complete code for a new tab in a lovelace dashboard

![complete weather dashboard](/Dashboards/LoveLace/Weather/Complete_weather_dashboard.png "complete weather dashboard")

1. you need to install the [clock-weather-card](https://github.com/pkissling/clock-weather-card)
2. you need to install the [hourly-weather](https://github.com/decompil3d/lovelace-hourly-weather)
3. you need to install the [compass-card](https://github.com/tomvanswam/compass-card)
4. you need to install the [horizon-card](https://github.com/rejuvenate/lovelace-horizon-card/)
5. you need to install the [rain-gauge-card](https://github.com/t1gr0u/rain-gauge-card)
6. you need to install the [mini-graph-card]https://github.com/kalkih/mini-graph-card


## Afvalwijzer

1. you need to install Afvalwijzer
2. upload the pictures in the www folder
3. use the yaml code (or make your own ;) )
4. Use automations to send triggers