Facilitate Migration

To facilitate HPM migration of one developer to another, the origianl github repo is duplicated and then altered to assist the new developer. 

original repo:
https://raw.githubusercontent.com/dmike3/Hubitat/master/hpm/repository.json

``` json
{
  "author": "n3! development",
  "gitHubUrl": "https://github.com/dmike3/",
  "payPalUrl": "https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=7TFJDAWDBTJL2&currency_code=USD&source=url",
  "packages": [
    {
      "name": "Xbox One Smartglass",
      "category": "Integrations",
      "location": "https://raw.githubusercontent.com/dmike3/Hubitat/master/hpm/xbox-smartglass/packageManifest.json",
      "description": "Xbox One Smartglass Intergration. The app and driver interface with the Xbox Smartglass Project giving local control of your Xbox One."
    },
    {
      "name": "Channels DVR",
      "category": "Integrations",
      "location": "https://raw.githubusercontent.com/dmike3/Hubitat/master/hpm/channels_dvr/packageManifest.json",
      "description": "This driver works with Channels DVR clients. It allows remote control features such as On/Off, Pause, Resume, Stop, Play Channel, mute, etc..."
    },
    {
      "name": "Weather Canada (OWM-EC)",
      "category": "Integrations",
      "location": "https://raw.githubusercontent.com/dmike3/Hubitat/master/hpm/weather%20canada%20(owm-ec)/packageManifest.json",
      "description": "Polls weather information from OpenWeatherMap and Weather Environment Canada (Alert RSS Feed - https://weather.gc.ca/)"
    }
  ]
}
```
