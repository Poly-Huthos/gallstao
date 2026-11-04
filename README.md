# Gällstaö Sky Now

A one-page phone viewer for the newest satellite images over Gällstaö (Ekerö, Stockholm):

- **Clouds**: Meteosat-12 GeoColour by day, infrared 10.5 µm at night
- **Fog & mist**: Night Microphysics RGB at night, Day Snow-Fog RGB by day
- **Rain**: satellite rain estimate, plus a link to SMHI's radar

Each image is centred on Gällstaö (red ring), stamped with the scan time in Swedish time, and refreshes every 10 minutes. Day or night products are picked from the sun's height. Three zoom levels: about 60, 250 and 900 km across.

Open `index.html` in a browser, or publish with GitHub Pages and add it to your phone's home screen.

Data: [EUMETSAT View](https://view.eumetsat.int) WMS (MTG FCI) and [SMHI](https://www.smhi.se).
