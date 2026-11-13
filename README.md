# Cubao Ukay-Ukay & Frames Map

An interactive map of thrift (ukay-ukay) stores around Cubao, Quezon City, and
the best places to hunt for vintage eyeglass frames and sunglasses.

**Live:** https://letsellahvate.github.io/cubao-thrift-map/

## What it does

- Pins 10 spots on a Leaflet map, colour-coded as **thrift / ukay**, **good for frames**
  or **farther trip**.
- Each store card gives the address or landmark, what it's good for, and tags.
  Tap a card to zoom the map to it.
- **Find my location** shows where you are, then draws a road route (via the public OSRM server)
  to the store you pick, with distance and driving time and a link to
  turn-by-turn directions in Google Maps. If no road route is available it falls
  back to a straight line and distance.
- Works on phones.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve
the folder:

```sh
python3 -m http.server 8000
```

## Stack

HTML, CSS and vanilla JavaScript, with [Leaflet](https://leafletjs.com/) 1.9.4,
OpenStreetMap tiles and OSRM routing. Hosted on GitHub Pages.

## Note

Store details were gathered from public listings and may change. Check opening
hours before you go.
