# infoboard

> Infoboard showing time, weather, calendar events, photos from local folder or online sources as background and Transport for London status updates.  
> Intended for Raspberry Pi, but should work on any machine with NodeJS available.

## Features

- Almost everything is configurable in `.env` file;
- Show current time and date;
- Calendar events from an iCal format link,
- Background images, changing every 60 seconds. Source of images can be:
  - a local folder,
  - view Exif information only for images from local folder,
  - [NASA Picture of the day](https://apod.nasa.gov/apod/astropix.html),
  - random image from [Unsplash](https://unsplash.com/),
  - curated images from [Pexels](https://www.pexels.com/),
  - both Unsplash and Pexels also support showing images tagged with current weather conditions: "light rain", "mostly clear" and so on,
  - weather tagged photos from [Flickr](https://www.flickr.com/);
- MP4 videos played as the background;
- Current weather and weekly forecast from [Tomorrow.io](https://www.tomorrow.io/) formerly ClimaCell;
- Additional weather details include:
  - humidity,
  - wind speed,
  - barometric pressure,
  - air quality (PM2.5 and PM10),
  - many more.
- Support for local [DHT sensor](https://www.google.com/search?q=DHT+sensor) (temperature and humidity); Check installation instructions [below](#dht-sensor-installing-and-troubleshooting);
- Transport for London status updates for tube, overground, dlr, tfl rail and tram;
- Transport for London bus timetable for bus stops you choose;
- COVID-19 stats from [Our World in Data](https://ourworldindata.org/coronavirus). Their GitHub repo [here](https://github.com/owid/covid-19-data/tree/master/public/data);
- [Magic Mirror](https://www.raspberrypi.org/blog/magic-mirror/) mode - no background images at all, just solid black background and all text is white. This gives best contrast to use behind a magic mirror.
- Everything, except for time can be folded or expanded by clicking on their icons;
- Two buttons at the bottom right corner allow skipping to the next image or skip the entire folder to the next one (for local images source only);
- If your browser supports programmatic fullscreen mode, a third button will appear to switch browser to fullscreen;
- Runs as a responsive website therefore can be accessed on any device;
- Available as [PWA](https://developers.google.com/web/progressive-web-apps/) (Progressive Web Application) - add a shortcut to infoboard that looks just like an app on your phone or tablet and don't bother using a browser.

## Installation

<p align="center"><img align="center" src="http://imgur.com/V4LtoII.png"/></p>
<p align="center">
  <a href="https://circleci.com/gh/nuxt/nuxt.js"><img src="https://badgen.net/circleci/github/nuxt/nuxt.js/dev" alt="Build Status"></a>
  <a href="https://ci.appveyor.com/project/nuxt/nuxt-js"><img src="https://badgen.net/appveyor/ci/nuxt/nuxt-js/dev" alt="Windows Build Status"></a>
  <a href="https://codecov.io/gh/nuxt/nuxt.js"><img src="https://badgen.net/codecov/c/github/nuxt/nuxt.js/dev" alt="Coverage Status"></a>
  <a href="https://www.npmjs.com/package/nuxt"><img src="https://badgen.net/npm/dm/nuxt" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/nuxt"><img src="https://badgen.net/npm/v/nuxt" alt="Version"></a>
  <a href="https://www.npmjs.com/package/nuxt"><img src="https://badgen.net/npm/license/nuxt" alt="License"></a>
  <a href="https://discord.gg/VApZF5W"><img src="https://badgen.net/badge/Discord/join-us/7289DA" alt="Discord"></a>
 </p>
 <p align="center">
  <a href="#partners" alt="Partner on Open Collective"><img src="https://opencollective.com/nuxtjs/tiers/partner/badge.svg" /></a>
  <a href="#sponsors" alt="Sponsors on Open Collective"><img src="https://opencollective.com/nuxtjs/tiers/sponsors/badge.svg" /></a>
  <a href="#backers" alt="Backers on Open Collective"><img src="https://opencollective.com/nuxtjs/tiers/backers/badge.svg" /></a>
  <a href="https://opencollective.com/nuxtjs"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>

</p>

> Vue.js Meta Framework to create complex, fast & universal web applications _quickly_.

## Links

- 📘 Documentation: [https://nuxtjs.org](https://nuxtjs.org)
- 👥 Community: [cmty.app/nuxt](https://cmty.app/nuxt)
- 🎬 Video: [1 minute demo](https://www.youtube.com/watch?v=kmf-p-pTi40)
- 🐦 Twitter: [@nuxt_js](https://twitter.com/nuxt_js)
- 💬 Chat: [Discord](https://discord.gg/VApZF5W)
- 📦 [Nuxt.js Modules](https://github.com/nuxt-community/modules)
- 👉 [Play with Nuxt.js online](https://glitch.com/edit/#!/nuxt-hello-world)

## Features

- Automatic transpilation and bundling (with webpack and babel)
- Hot code reloading
- Server-side rendering OR Single Page App OR Static Generated, you choose :fire:
- Static file serving. `./static/` is mapped to `/`
- Configurable with a `nuxt.config.js` file
- Custom layouts with the `layouts/` directory
- Middleware
- Code splitting for every `pages/`

Learn more at [nuxtjs.org](https://nuxtjs.org).
