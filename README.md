# React Weather

<img src="https://user-images.githubusercontent.com/25284536/90274607-2535a000-de76-11ea-9d21-ab8c3e68b3a9.png" width="400"> <img src="https://user-images.githubusercontent.com/25284536/90274626-29fa5400-de76-11ea-97a7-c6b67ec2f66a.png" width="400">

## Tech Stack

**React, Typescript, Redux, StyledComponents**

## Features

- **Weather forecast for any city or place**
- **Extended 7 days forecast**
- **Find user location weather by utilizing GeolocationAPI**
- **One-click Celcius to Fahrenheit conversion and vice versa**
- **Dark Mode**

## Getting Started

First you need an API key from OpenWeatherMap, you can get one by creating an account on their website.
After you got your API key, create a **.env** file at root directory of project, copy the line below to the file and replace YOUR_KEY with your OpenWeatherMap API Key.

```
REACT_APP_WEATHER_API_KEY=YOUR_KEY
```

Finally clone this repository, install dependencies and run the local server

```bash
git clone https://github.com/esnz/reactweather.git
```

```bash
cd reactweather
npm install
npm start
```
