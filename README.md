# truck-weather
## Endpoint
"https://api.open-meteo.com/v1/forecast?latitude=35.22709&longitude=-80.84313&current=temperature_2m,wind_speed_10m,is_day,weather_code,precipitation&timezone=America%2FNew_York&wind_speed_unit=mph&temperature_unit=fahrenheit"

## What I changed using the docs
I added `precipitation`.
Before: Original Link source - "https://api.open-meteo.com/v1/forecast?latitude=30.27&longitude=-97.74&hourly=temperature_2m,wind_speed_10m&current=temperature_2m"
After: the Precipitation has been added to the request - "https://api.open-meteo.com/v1/forecast?latitude=35.22709&longitude=-80.84313&current=temperature_2m,wind_speed_10m,is_day,weather_code,precipitation&timezone=America%2FNew_York&wind_speed_unit=mph&temperature_unit=fahrenheit"


## Live site
https://paulettedejesus.github.io/truck-weather/