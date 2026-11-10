# Where in the World

A hand-drawn, spinning 3D globe for logging your travels. Color in the countries you've been to, drop pins on cities, star the places you want to go, and keep an airmail postcard for each country with notes and photos.

## Using it

- **Been there:** tap a country or city to color it in. Visited cities get a pin.
- **Want to go:** tap a city to add a star to your wish list.
- **Postcard:** tap a country to write a postcard and add photos.
- **Erase:** tap to remove a mark.
- **Search:** about 140,000 towns, regions and islands.
- **Flight lines:** the plane button shows your recent hops, every hop, or a replay of your travels.

## Saving

Your globe saves in your own web browser.

- Press **Save changes** (or Ctrl/Cmd + S) after editing. The button turns yellow when you have unsaved changes.
- Saves stay in that browser on that device. Nobody else can see them.
- Clearing your browser's site data deletes your globe, so use **Export backup** in the journal now and then. **Import backup** loads a backup on another device or browser.

## Putting it online with GitHub Pages

1. Create a new repository on GitHub and upload every file in this folder (keep them all in the top level).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

Opening `index.html` straight from your computer mostly works, but the browser blocks the search list and close-up map layers on files opened that way. To test it locally, run `python3 -m http.server` in this folder and open `http://localhost:8000`.

## Credits

- Country shapes, rivers, lakes and city areas: [Natural Earth](https://www.naturalearthdata.com/) (public domain), via [world-atlas](https://github.com/topojson/world-atlas).
- Towns and cities: [GeoNames](https://www.geonames.org/) (CC BY 4.0), via [all-the-cities](https://github.com/zeke/all-the-cities).
- Regions: [countries-states-cities-database](https://github.com/dr5hn/countries-states-cities-database) (ODbL 1.0).
- Libraries: [D3](https://d3js.org/) and [topojson-client](https://github.com/topojson/topojson-client).
- Fonts: Google Fonts (Pinyon Script, Kalam, IM Fell English, Josefin Sans, Alfa Slab One).
- Background image (`swirl-bg.jpg`): replace this with an image you have the rights to share if it isn't your own.
