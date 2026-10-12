# States I've Been To

A tap-to-fill map of the 50 U.S. states plus D.C. Pick a level from the map key, then tap states to mark them:

- **Lived there** (pink)
- **Stayed overnight** (green)
- **Visited**
- **Passed through** (purple)

An interstate-style shield keeps your count out of 50. A state index below the map gives every state a dropdown, which helps with small states and keyboard use. "Copy my summary" copies your list as text.

## Run it

It's a single static page. Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works).

Your map is saved in your browser's local storage, so it stays on the device and browser you used.

## Built with

- [d3 v3](https://d3js.org/), [topojson](https://github.com/topojson/topojson) and the U.S. state shapes bundled with [Datamaps](https://datamaps.github.io/), loaded from cdnjs
- System font stack that prefers SF Hello / SF fonts on Apple devices
