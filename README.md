# Firepad Replay

Firepad Replay is history navigator of Firepad and walks the user through the complete change log of an editor.

Currently in its expiremental state, needs a complete design overhaul. First prototype to get things working.
**Caution: DO NOT USE in current stage**

## Sources
* Based on Brunch(https://github.com/brunch/brunch) template and Firepad source code(https://github.com/firebase/firepad)

* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * Brunch plugins and app dependencies: `npm install`
* Run:
    * `brunch watch --server` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `brunch build --production` — builds minified project for production
