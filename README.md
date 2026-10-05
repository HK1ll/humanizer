# Humanizer

Rewrite stiff or AI-sounding text so it reads like a person wrote it.
Works in English, Arabic and other languages.

## Features
- Tone: Casual, Natural, Professional, Academic
- Change level: Light, Medium, Strong
- Deep mode: a second editing pass that removes leftover AI patterns
- Match my writing style: paste your own writing so the result sounds like you
- Live streaming output, Stop button, Copy button

## How it works
The site is a single static `index.html` with no server.
Each visitor enters their own Anthropic API key (from console.anthropic.com).
Requests go straight from the browser to Anthropic's API. The key is only
saved on the visitor's own device if they tick "Remember key".

## Run locally
Open `index.html` in a browser.
