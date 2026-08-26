# Weather Finder

A React weather app that looks up current conditions for any city, state, and country using the OpenWeatherMap API.

## Features

- Search weather by city, state/region, and country
- Displays temperature, humidity, and current conditions
- Clean, responsive UI with a full-bleed background image

## Tech Stack

- **Frontend:** React 16.8.6 (Create React App)
- **API:** [OpenWeatherMap](https://openweathermap.org/api)
- **Deployment:** GitHub Pages (`gh-pages`)

## Running Locally

This project was built with an older version of `react-scripts` (3.0.1), which has a known incompatibility with `fsevents` on modern Node versions (18+) via macOS. To run it locally:

```bash
nvm install 16
nvm use 16
npm install
npm start
```

You'll also need an OpenWeatherMap API key. Create a `.env` file in the project root:

## Known Issues

- Dependency tree includes many outdated packages (flagged by GitHub Dependabot) due to the project's 2019-era `react-scripts` version. These are dev dependencies and don't affect runtime behavior.

## Status

Fully functional — tested locally with live API calls returning real weather data.
