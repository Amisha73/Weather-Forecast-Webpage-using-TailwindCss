# Weather Forecast Webpage

## Project Overview

This project is a simple weather forecast webpage that allows users to check the weather for a specific city or their current location. The application fetches weather data from the OpenWeatherMap API and displays it in a user-friendly format.

## Features

- **City Search**: Users can enter a city name to get the current weather.
- **Current Location**: Users can fetch weather data based on their current geographical location.
- **Recently Searched Cities**: The application saves and displays a dropdown of recently searched cities for quick access.
- **Dynamic Weather Display**: The weather information is displayed with relevant icons and data.

## Technologies Used

- **HTML**: Structure of the webpage.
- **Tailwind CSS**: Styling of the webpage (linked via `output.css`).
- **JavaScript**: Functionality for fetching weather data and handling user interactions.
- **OpenWeatherMap API**: Used to fetch weather data.
- **Fontawesome CDN**: Use for icons.

## Tailwind CSS Installation Guide

This guide provides step-by-step instructions for installing and setting up Tailwind CSS in your project.

### 1. Install Tailwind CSS and CLI 
Use npm to install both `tailwindcss` and `@tailwindcss/cli`:  `npm install tailwindcss @tailwindcss/cli`

### 2. Import Tailwind in your CSS 
Import to your main CSS file:  `@import "tailwindcss";`.

### 3. Start the Tailwind CLI build process
Run the CLI tool to scan your source files for classes and build your CSS:  `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`

### 4. Start using Tailwind in your HTML
Add your compiled CSS file to the <head> and start using Tailwind’s utility classes to style your content:  `<link href="./output.css" rel="stylesheet">`


## How to Use

1. **Enter City Name**: Type the name of the city in the input field and click the "Check" button.
2. **Use Current Location**: Click the location icon to fetch weather data based on your current location.
3. **Select Recent Cities**: Use the dropdown to quickly select from recently searched cities.
