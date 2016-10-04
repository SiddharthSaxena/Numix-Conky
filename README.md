# Numix-Conky :sunny: :umbrella: :cloud: :snowflake: :snowman:

A theme for [conky](https://github.com/brndnmtthws/conky) version `1.9.x` powered by [OpenWeatherMap](http://openweathermap.org/).

---

* [Installation](#installation)
* [API-key](#api-key)
* [City](#city)
* [Language](#language)
* [Units](#units)
* [Credits](CREDITS.md)
* [Preview](#preview)

---

####Installation:

* Install **conky**, **curl** and **jq**.

* Make sure you have the **Droid Sans** font installed.

* Move the `.assets` folder into your `~` dir.

---

###API Key

Register a private API key on [OpenWeatherMap](http://openweathermap.org/) to get weather data.

Place the API key in the `template6` variable inside the `.conkyrc`file.

---

###City

[Find the ID of your city](http://openweathermap.org/help/city_list.txt) and place it inside the `template7` variable inside the `.conkyrc` file.

---

###Language

By default this conky will use your default locale.

Edit the `template9` variable in the `.conkyrc` file to change the language.

[See the list of supported languages](http://openweathermap.org/current#multi)

**NOTE:** `God-mode` has some hardcoded text that won't get translated, but you can edit it manually.

---

###Units

Edit the `template8` variable inside the `.conkyrc` file to change the units.

---
