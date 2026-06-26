# Nimbus — Weather App

Nimbus is a responsive weather dashboard that helps users quickly check current weather, hourly forecasts, and a 7-day outlook in one clean interface. It uses the OpenWeatherMap API and stores user preferences locally, so repeat users do not need to set their API key, preferred unit, or default location every time.

## Live Demo

[View the live app](https://jagjitkaur14.github.io/weather-App/)

## Project Overview

Weather apps are often used in quick, repeat-checking moments: before leaving for work, planning travel, checking rain chances, or deciding what to wear. Nimbus focuses on reducing that repeated effort by saving the user’s preferred location, temperature unit, and API key locally in the browser.

## User Problem

Users need a fast and simple way to check weather conditions without repeatedly searching for the same city or changing the same settings every time.

## Solution

Nimbus provides a single-page weather dashboard where users can:

- Search for weather by city
- View current temperature and weather condition
- Check hourly forecast for the next 24 hours
- View a 7-day forecast
- Switch between Celsius and Fahrenheit
- Save a default location
- Save preferences locally in the browser
- View useful weather details such as humidity, wind, pressure, visibility, UV index, sunrise, and sunset

## Features

- Real-time weather data using OpenWeatherMap API
- City-based weather search
- Current weather dashboard
- Hourly forecast for the next 24 hours
- 7-day weather forecast
- Celsius and Fahrenheit unit toggle
- Saved default location
- Recent location support
- Local API key storage using browser localStorage
- Weather details including humidity, wind, pressure, visibility, UV index, and dew point
- Sunrise and sunset information
- Daily weather summary notification option
- Responsive UI for desktop and mobile screens

## Tech Stack

- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API
- Browser localStorage
- GitHub Pages

## Product Thinking

### Target Users

People who frequently check weather for daily planning, office commute, travel, or outdoor activities.

### Core Use Cases

1. A user wants to quickly check today’s weather before leaving home.
2. A user wants to know whether they should carry an umbrella.
3. A user wants to compare hourly weather changes through the day.
4. A user wants to save their default city and avoid repeated searches.
5. A user wants to switch between Celsius and Fahrenheit based on preference.

### Product Decisions

- Saved preferences reduce repeat effort for returning users.
- Hourly and 7-day forecasts support both short-term and weekly planning.
- Unit toggle supports users from different regions.
- Local storage avoids requiring a backend for a beginner-friendly project.
- Settings drawer keeps the main dashboard clean while still giving control to users.

## Success Metrics

If this were a production product, success could be measured through:

- Repeat usage rate
- Number of saved default locations
- Number of successful weather searches
- Reduction in repeated setup actions
- Engagement with hourly and 7-day forecast sections
- Notification opt-in rate

## Screenshots

Add screenshots inside this folder before publishing the final portfolio version:

```text
assets/screenshots/home-screen.png
assets/screenshots/weather-dashboard.png
assets/screenshots/settings-drawer.png
```

Suggested screenshots:

1. API key / launch screen
2. Main weather dashboard after searching a city
3. Settings drawer with unit and default location options

## How to Use

1. Open the live demo.
2. Enter your OpenWeatherMap API key.
3. Search for a city.
4. View current weather, hourly forecast, and 7-day forecast.
5. Use settings to update unit preference or save a default location.

## Getting Started Locally

```bash
git clone https://github.com/jagjitkaur14/weather-App.git
cd weather-App
```

Then open `index.html` in your browser.

## API Key Setup

Nimbus uses OpenWeatherMap API. You can create a free API key from OpenWeatherMap and paste it into the app when prompted.

The API key is stored only in the browser using localStorage. It is not saved in the repository.

## Recommended Repository Structure

The current project works as a single-page app. For better maintainability, the next improvement should be splitting the code into separate files:

```text
weather-App/
├── index.html
├── style.css
├── script.js
├── assets/
│   └── screenshots/
└── README.md
```

## Future Improvements

- Split HTML, CSS, and JavaScript into separate files
- Add loading skeletons for a smoother user experience
- Add better error messages for invalid API keys and network failures
- Add current-location weather using browser geolocation
- Add weather-based recommendations such as “Carry an umbrella” or “High UV, use sunscreen”
- Add accessibility improvements for keyboard navigation and screen readers
- Add automated testing for key user flows
- Add screenshots and demo GIF to the README

## Resume Description

Built a responsive weather dashboard using OpenWeatherMap API with live weather search, hourly forecast, 7-day forecast, unit toggle, saved default location, and local preference storage. Improved product thinking by defining user problems, core use cases, product decisions, and future roadmap.

## LinkedIn Project Description

Nimbus Weather App is a responsive weather dashboard designed to help users quickly check current weather, hourly forecasts, and 7-day forecasts. The app includes saved preferences, Celsius/Fahrenheit toggle, default location, sunrise/sunset details, UV index, and OpenWeatherMap API integration.

## Author

Jagjit Kaur

## License

This project is open for learning and portfolio use.
