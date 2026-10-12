# Carbon footprint tracking system — live project overview

[Open the live project page](https://charlesnkuba.github.io/projects/carbon-footprint/)

This is the live overview of Charles Nkuba's final-year project, **Design and Implementation of a Web-Based Carbon Footprint Tracking System**. The application is in development.

## Current published scope

The static page describes the project objectives, planned Flask/SQLite architecture and implementation phases. It does not calculate emissions, authenticate users or run the working Flask application. The application source has not yet been supplied to this repository.

## Planned application

User activity capture for transport, electricity and fuel; predefined emission factors; historical records; dashboards; and rule-based recommendations. AI integration is excluded.

## Updating during development

The live URL is stable. Edits committed to `main` in the portfolio repository trigger its configured GitHub Pages deployment. Update the project page as features are verified. To publish the real application, first add its current source to GitHub and configure a host that runs Flask; GitHub Pages cannot run that backend.

Do not put passwords, secret keys, personal databases or private activity records in public source. Use an environment example and an empty or fictional dataset if application code is later added.

## Preview

Open `index.html` directly in a browser, or serve the portfolio repository with `python3 -m http.server 8000` and visit `/projects/carbon-footprint/`.
