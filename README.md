# GIST 604B – WebGIS & Full-Stack Orchestration
**Student:** Lydia Barker
**Course:** GIST 604B – Open Source GIS
**Module:** Module 6 - WebGIS With Leaflet
**University of Arizona**

## Project Description
This project is a WebGIS application built with HTML, CSS, JavaScript, and Leaflet. It displays multiple GeoJSON datasets on an interactive web map with custom styling, popups, and layer organization. The finished map is published and publicly accessible via GitHub Pages.

## Tools and Technologies
- Leaflet
- HTML, CSS, and JavaScript
- Visual Studio Code
- Node.js

## What I Did
- Forked the assignment repository and cloned it to a local development environment using VS Code and Git
- Prepared and loaded three GeoJSON datasets (point, line, polygon) into the data folder
- Built a Leaflet web map centered on my area of interest, including a basemap, zoom controls, and styled GeoJSON layers
- Added interactive popups using feature attribute data
- Published the completed web map as a live site using GitHub Pages

## How to View / Run
Live map: https://lydia-barker.github.io/gist604b-webgis-leaflet-sp26/ 
- Clone the repository and open it in VS Code
- Open a terminal and run npm install to install dependencies
- Run npm start to start the local development server
- Open your browser and go to http://localhost:8080 to view the changes you make on VS

## Repository Structure
```
/
├── data/
│   ├── Bicycle_Boulevards.geojson
│   ├── Modern_Streetcar_Stops_-_Open_Data.geojson
│   └── TPRD_PROPERTIES_OMS_AGOVW_.geojson
├── js/
│   └── map_withcode.js
├── css/
│   └── styles.css
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── .gitignore
```

## Notes
- Replace the placeholder filenames in `data/`, `js/`, and `css/` with your own files.
- All GeoJSON datasets must be in WGS84 (EPSG:4326) and placed in the `data/` folder.
- Run `npm install` to install dependencies and `npm start` to launch the local development server.
- Open `http://localhost:8080` in your browser to preview your map during development.
- The final web map is published using GitHub Pages.
