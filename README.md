# Pocket Wings

A small Flappy Bird-inspired game with original canvas artwork. Press Space, the up arrow, or tap the game to flap. Pass pipes to score; your best score stays in this browser. Flights pause when the tab is hidden.

## Run

Open `index.html` directly, or run `python3 -m http.server 8080` in this directory and visit http://localhost:8080.

## Deploy

Import this repository in Vercel, choose **Other** as the framework, leave the build command empty, and use the repository root as the output directory. No dependencies or environment variables are required.

## How it works

The browser draws a canvas every animation frame. Gravity pulls the bird down; a tap gives it upward velocity. Pipes move left, collisions end the flight, and passing a pipe adds a point. Best scores use localStorage.
