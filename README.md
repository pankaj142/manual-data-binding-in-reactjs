live-server is used for seeing the html changes inside the browser.

Use commands to start app-

1. yarn install
2. start babel to watch changes in src/app.js file and convert them => babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch
3. Install live-server package globally => npm install live-server -g
4. live-server public (in another terminal window)