<div align="center">

# Wetter

A user-friendly weather app that provides real-time weather data and forecasts for any location.

[![Use Online](https://img.shields.io/badge/▶_Use_it_Online-2ea44f?style=for-the-badge)](https://ef-krbg.github.io/wetter/)
[![Download](https://img.shields.io/badge/⬇_Download-0969da?style=for-the-badge)](https://github.com/ef-krbg/wetter/archive/refs/heads/main.zip)

</div>

---

## About

Wetter is a single-page weather app: type in a city, and it pulls live conditions and an hourly outlook, then changes its own background to match the weather. Everything runs client-side in the browser — no backend, no build step.

## Screenshots

<p align="center">
  <img src="screenshots/main.png" alt="Wetter App main screen" width="500">
</p>

## Features

- **Live conditions** — current temperature, description, high/low, wind speed, humidity, and pressure for any city.
- **Hourly forecast** — a scrollable 24-hour outlook in 3-hour steps.
- **Weather-matched backgrounds** — the background image changes to match the current conditions (clear, clouds, rain, snow, thunderstorm, mist/fog).
- **Simple search** — type a city and press Enter or click the button; a dedicated button lets you search a new city afterward.
- **German interface** — labels and results are in German.

---

## Getting Started

Click **Use it Online** above to open the app straight in your browser — nothing to install.

Click **Download** to get a `.zip` of the app. Unzip it and open `index.html` in your browser to run it offline.


## Project Structure

```
wetter/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   ├── background.png
│   │   ├── clear.png
│   │   ├── cloud.png
│   │   ├── falsch.png
│   │   ├── hagel.png
│   │   ├── rain.png
│   │   ├── ricon.png
│   │   ├── snow.png
│   │   ├── sonne.png
│   │   ├── sturm.png
│   │   ├── thunder.png
│   │   └── trub.png
│   └── js/
│       └── main.js
├── LICENSE
└── README.md
```

## Tech Stack

HTML · CSS · JavaScript · [Bootstrap](https://getbootstrap.com/) · [OpenWeatherMap](https://openweathermap.org/) forecast data

## License

Distributed under the MIT License. See `LICENSE` for details.

---

<div align="center">

Enes Fatih Karabag — [github.com/ef-krbg](https://github.com/ef-krbg)

</div>
