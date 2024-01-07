# WeatherApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.1.

## Demo

Check out the live demo of the application [here](https://659ae24bb11170b34e48d20c--effortless-strudel-27f092.netlify.app/).

## Screenshots

<img src="/screenshot1.JPG" alt="Simple currency converter"/>

<img src="/screenshot2.JPG" alt="Simple currency converter"/>
  
## RapidAPI Weather API Integration

This project uses the RapidAPI Weather API. Follow these simple steps to set it up:

1. **Create an Account:**
   Sign up on [RapidAPI](https://rapidapi.com/), then subscribe to the WeatherAPI by visiting [Subscribe to the RapidAPI Weather API here](https://rapidapi.com/apidojo/api/weather338/).

2. **Update API Key and Host:**
   After subscribing, go to `src/Environment/EnvironmentVariable.ts` and replace the API key and host with your own values. You received these when you subscribed to the API at RapidAPI.

3. **Weather API URLs:**
   In the `src/Environment/EnvironmentVariable.ts` file, update the API URLs with the specific endpoints provided by the RapidAPI Weather API.
  
     - weatherApiLocationBaseURL: 'https://your-rapidapi-weather-api-url/locations/search?',
     - weatherApiForecastBaseURL: 'https://your-rapidapi-weather-api-url/weather/forecast?',
     - xRapidApikeyValue: 'your-api-key',
     - xRapidApiHostValue: 'your-api-host'

## Install Dependencies

Run `npm install` to install the required npm packages.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
