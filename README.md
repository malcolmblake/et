# GIS Boundary App

This is an example app demonstrating the boundary function from Mapbox.

## TL;DR

To start the project first clone or download locally.

Both `gis-api` and `gis-app` folders require a `.env` file to run.

---

To run the API :

```sh
# From this folder
cd gis-api
npm start
# or
npm run start
```

Read more here: [/gis-api/README.md](/gis-api/README.md)

---

To run the App:

```sh
npm run build
npm run start
```

Read more here: [/gis-app/README.md](/gis-app/README.md)

---

Read on if you want more info.

## Overview

This App works with or without user input.

If user input (a button click) is present;

- The App will request coordinates from the API.
- The API will return a set of random coordinates within the preset boundary limit along with a bounding box value and the outline for the map

## Next Steps

What I would like to do with this is add a lot more features. I have barely scratched the surface and I have enjoyed what I have managed to achieve so far.

I found React and the basic boilerplate from Mapbox to be quite tempermental. The `react-mapbox-gl` package has been a lot better just for starters.

I would normally make an app more secure before putting it out there so, with that caveat out of the way, be careful what you request. ;)
