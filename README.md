# SSN Virginia-class Submarine Sonar Dashboard - Modified

This is a modified version of the SSN Virginia-class Submarine Sonar Dashboard with the radar taking up approximately 75% of the screen.

## Changes Made

- **Grid Layout**: Changed from fixed pixel columns (`380px 680px 450px`) to responsive percentage-based layout (`12.5% 75% 12.5%`)
- **Canvas Size**: Updated canvas to use `height: 95%` with a minimum height of `500px` for better responsiveness
- **Responsive Design**: Added media queries for smaller screens to ensure the dashboard remains usable on tablets and mobile devices
- **Panel Layout**: Made left and right panels scrollable when content exceeds available space on smaller screens

## How to Use

Simply open `index.html` in your web browser.

For a live demo, visit: [View on GitHub Pages](https://theTotesmagoats.github.io/sonar-radar-dashboard-modified/)

## Features

- Real-time sonar simulation with moving contacts
- 3D-style CRT display effects with scanlines and vignette
- Interactive radar sweep animation
- Audio feedback (sonar pings, explosions)
- Torpedo firing mechanics
- Contact tracking and logging system

## Original Source

Based on the original SSN Virginia-class Submarine Sonar Dashboard simulation.
