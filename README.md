# Numix-Conky :sunny: :umbrella: :cloud: :snowflake: :snowman:

A theme for [conky](https://github.com/brndnmtthws/conky) based on [Harmattan](https://github.com/zagortenay333/Harmattan/) powered by [OpenWeatherMap](http://openweathermap.org/).

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

* Install **conky**, **curl** and **jq**. (sudo apt-get install conky-all curl jq)

* Make sure you have the **Droid Sans** font installed.

* Move the `.assets` folder into your `~` dir.

---

###API Key

Register a private API key on [OpenWeatherMap](http://openweathermap.org/) to get weather data.

Place the API key in the `template6` variable inside the `.conkyrc`file.

---

###City

Find the [ID](http://openweathermap.org/help/city_list.txt) of your city and place it inside the `template7` variable inside the `.conkyrc` file.

---

###Language

By default this conky will use your default locale.

Edit the `template9` variable in the `.conkyrc` file to change the language.

[See the list of supported languages](http://openweathermap.org/current#multi)

---

###Units

Edit the `template8` variable inside the `.conkyrc` file to change the units.

---

<img src="http://www.siddharthsaxena.weebly.com/files/theme/Numix-Conky.png" id="preview">
