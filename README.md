# Order Summary Component challenge

![Screenshot of the order summary component challenge ](./src/images/desktop-screenshot.png)

<div align="center">
  <img src="./src/images/logo-html5.svg">
  <img src="./src/images/logo-css3.svg">

  <img src="./src/images/logo-parceljs.png">
  <img width="72px" src="./src/images/logo-parceljs.svg">
</div>

## Overview

_A tiny component to present an order summary._

<br />

## Links

<p>
<a href="https://github.com/AngeliqueDF/order-summary-component-challenge">GitHub repository</a> • <a href="https://cozy-entremet-aecca6.netlify.app/">Live demo </a>
</p>

<br />

## How to run the project

1. `git clone https://github.com/AngeliqueDF/order-summary-component-frontend-mentor.git MY-FOLDER-NAME`
2. `cd MY-FOLDER-NAME`
3. `npm install`
4. `npm start`
5. Visit [http://localhost:1234](http://localhost:1234)

<br />

## The challenge

> Your challenge is to build out this order summary card component and get it looking as close to the design as possible.[...]
>
> Your users should be able to:
>
> - See hover states for interactive elements.
>
> _[From Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)_

## Description

This project is my solution to the Order Summary Component challenge from Frontend Mentor.

The most challenging part was deciding on the HTML structure with the information given.

I still find that I relied to much on `<div>` elements.
Any suggestion on the markup is welcome!

<p align="center">
<img src="./src/images/mobile-screenshot.png" width="375" height="660px" alt="Screenshot of the order summary component on mobile.">

## Features

- Responsive.
- Semantic and accessible HTML5.

<br />

## Technologies

- Semantic `HTML5`.
- `SCSS`.
- `Flexbox`.
- Bundled with `parcel` (v2).

<br />

## How I built this project

1.  Started by structuring the page with semantic and accessible HTML.
2.  Styled the page with a mobile-first approach.

### What I learned

I added `parcel` to have an idea of how to use it compared to `webpack` and `gulp`. I didn't have to write any JavaScript or add any loader, even for SCSS support! The plugin needed was installed automatically.

All it required to work was (updated):

1. Installing `parcel`.
2. Start working using `npm run build`:

```json
"source": "/src/index.html",
  "scripts": {
    "start": "parcel",
    "build": "parcel build"
  },
```

With this configuration:
- `"source": "/src/index.html"` indicates the path to the entry of the app.
- `npm start` starts a local server, enables live reload for development.
- `npm run build` generate a `/dist` folder to use for deployment.

This was ideal for such a small project.

<br />

## Sources

- [Order summary component by Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

## Useful references

1. [Why You Should Choose HTML5 article Over section](https://www.smashingmagazine.com/2020/01/html5-article-section/)

## Useful extensions

- [W3C Web Validator - Visual Studio Marketplace. I use this extension to check the validity of HTML code from the editor.](https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator)
