# The Weather App

> The Ultimate Weather App feat. OpenWeatherMap API.

_Design inspired by [Anastasia Kas](https://dribbble.com/shots/6250202-Daily-UI-037-Weather)_

## Context

You are a senior member of a team tasked with developing the web front-end of a new, intelligent weather forecasting service. While the data science team are reading the clouds, the Venture is keen to get a proof of concept up and running.

The application should use the OpenWeatherMap API, as the eventual smart data will have a similar structure.

Users must be able to provide their location, and see at least the current weather, temperature, sunrise and
sunset times.

Framework and look and feel are entirely at your discretion. Consider how you can display the information clearly and visually. If you need some inspiration, try Dribbble or Behance!

The site is expected to be accessed primarily by mobile devices but should support all major browsers.

## Challenge

### Required

- Build and host a web application that uses the OpenWeatherMap API (sign up to access the API) to retrieve and display current weather information for a user-entered location.
- The information shown must include: current weather, temperature, sunrise and sunset times.
- The application must be resilient and user-communicative regarding errors.
- Ensure that the application meets basic accessibility criteria, and uses good semantic HTML.

### Stretch

- Display the remaining information from the API call: visibility, wind, humidity, etc.
- Provide some personalisation settings. Preferred units (°C/°F), for example.
- Store and recall these settings from local storage, as well as the user’s recently entered locations.
- Add appropriate tests to suit the scenario.

## Solution

This app has been done with [CRA](https://create-react-app.dev/) and [TailwindCSS](https://tailwindcss.com/), so the default scripts still apply

```bash
yarn start // to start the app
yarn build // to build the app
yarn test // to run tests with jest
```

## Future work aka extra TODOs

- dark vs light mode based on the time of the day
- change image on city search
- unit tests with mocks
  - geo api
  - weather api + formatted values
- toasts for errors
- accessibility
  - keyboard navigation
  - labelledBy
