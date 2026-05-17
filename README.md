[Русский](./README.ru.md) | English

# Dostaffkin — parcel delivery service

Live demo: https://roman-mikhaylov.github.io/dostaffkin/

This repository contains my implementation of **Dostaffkin**, a web application for booking and tracking parcel deliveries within the country and worldwide. The app is built with **Angular** and deployed to **GitHub Pages**.

## Features

- Landing page describing the delivery service
- Order screen with a form for creating a shipment
- Tracking screen where the user can check parcel status by tracking number
- Basic validation of key form fields

## Tech stack

- Angular (standalone components)
- TypeScript
- HTML, CSS
- GitHub Pages for static hosting

## Live demo

The application is available at:

https://roman-mikhaylov.github.io/dostaffkin/

## Run locally

```bash
git clone https://github.com/roman-mikhaylov/dostaffkin.git
cd dostaffkin
npm install
npm start        # or: ng serve
```

Then open `http://localhost:4200` in your browser.

## Build & deploy

The production build is created with Angular CLI:

```bash
npm run build    # or: ng build
```

The compiled static files are deployed to GitHub Pages and served from:

https://roman-mikhaylov.github.io/dostaffkin/
