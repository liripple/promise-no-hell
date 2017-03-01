# Callback Hell vs Promises

- Open `callback_hell.js` in your editor
- Open `index.html` in a browser to see the page in action
- Notice how each callback is nested within another callback
- `$.get(url)` will return a Promise that you can then use `.then()` on to get the results or to handle the error
- Use the Promise-version of `$.get` and chain them so as to get rid of the nested callbacks
- Check your results by refreshing `index.html` in a browser
- Check your browser's console that you have no errors
