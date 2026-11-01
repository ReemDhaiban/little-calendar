# Little Calendar

A small desktop calendar widget built with Electron. It sits on your screen as a frameless, transparent window and shows today's date and month in a pixel-style font with a soft purple frame.

## Features

- Shows the current day and month
- Frameless, transparent window that blends into your desktop
- Drag it anywhere on the screen
- Pixel-art look using the Pixelify Sans font

## Built with

- [Electron](https://www.electronjs.org/)
- HTML, CSS and JavaScript
- [Pixelify Sans](https://fonts.google.com/specimen/Pixelify+Sans) from Google Fonts

## Getting started

You need [Node.js](https://nodejs.org/) (which includes npm) installed.

```bash
git clone https://github.com/rdaiban98-hash/little-calendar.git
cd little-calendar
npm install
npm start
```

## Project structure

```
little-calendar/
├── main.js          # Electron main process: creates the widget window
├── index.html       # Widget layout
├── styles.css       # Widget styling and frame backgrounds
├── script.js        # Fills in today's day and month
├── assets/
│   ├── outer-frame-bg.png
│   └── inner-frame-bg.png
└── package.json
```

## Ideas for later

- Update the date automatically at midnight
- Show the weekday
- Start the widget when the computer starts
