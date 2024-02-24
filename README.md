# Prototype

## Installation
Clone this git repo
In the project folder, run `npm install`

## Starting the server
In this project folder, `npm run dev` will start a live-updating local server. Going to `http://localhost:1234` should load your game, and every time you save changes it'll live-update. Check the CLI output, it may end up spitting out a different number. If it doesn't work, you might also try `http://localhost:1234/index.html`, sometimes it's finicky

## Production Builds
`npm run build` will spit out a production build of your game in the `dist` folder. As long as you put any static images in the `images` folder in the root, they will be copied over to these production builds.