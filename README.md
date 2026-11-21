
# Weather App

A responsive React weather application that searches for a city and displays its current temperature, humidity, wind speed, and weather icon.

## Features

- Search weather by city name
- Display current temperature in Celsius
- Show humidity and wind speed
- Match weather conditions to clear, cloudy, rainy, snowy, or drizzle icons
- Load London weather by default

## Tech Stack

- React 19
- Vite
- OpenWeatherMap API
- ESLint

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm
- An OpenWeatherMap API key

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd weather-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and add your OpenWeatherMap API key:

   ```env
   VITE_APP_ID=your_openweathermap_api_key
   ```

   You can create a free API key from the [OpenWeatherMap website](https://openweathermap.org/api).

### Run the App

Start the development server:

```bash
npm run dev
```

Open the local URL printed by Vite in your browser.

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview the production build locally |

## Usage

1. Enter a city name in the search field.
2. Click the search icon.
3. View the current temperature, location, humidity, wind speed, and weather condition.

The app initially loads weather data for London.

## Project Structure

```text
weather-app/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Weather.jsx
│   │   └── Weather.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── eslint.config.js
├── index.html
├── package.json
└── vite.config.js
```

## Environment Variables

| Variable | Required | Description |
| --- | --- | --- |
| `VITE_APP_ID` | Yes | OpenWeatherMap API key used to request weather data |

Restart the Vite development server after changing environment variables.

## Project URL
https://roadmap.sh/projects/weather-app
