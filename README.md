# beestMet
## yet another Limnoria weather plugin

### requires:
```
Limnoria
Python 3
python-requests
API key from avwx.rest for METAR
API keys from mapquestapi.com and openweathermap.org for current weather
```

### usage:
* `metar <ICAO code>` for station METAR results
* `met <location>` for current weather
* `met <nick>` retrieves weather for a nick registered in a `met.json` file
* `met` will retrieve weather for your own nick

> `met.json` is a simple list of nicks and locations in `key: value` pairs


### todo
* 5-day forecasts
* optionally use owm's own geo
* less spaghetti code

### bugs
* probably lots
