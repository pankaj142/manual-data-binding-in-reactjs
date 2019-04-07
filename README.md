Goal- To understand the data binding in reactjs.
This is Reactjs App, no react components are used, data binding is done manually.

Reactjs uses Virtual DOM to check which minimal part of the UI is get modified when re-rendering the DOM. And only that part is re-rendered. So, cost of re-rendering UI is minimal.

live-server is used for seeing the html changes inside the browser.

Use commands to start app-

1. yarn install
2. babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch
3. npm install live-server -g (Install live-server package globally)
4. live-server public (in another terminal window)
