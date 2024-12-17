## Leaflet
---

# Earthquake Visualization Dashboard

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [File Structure](#file-structure)
- [Author](#author)

---

## Description

The **Earthquake Visualization Dashboard** is a web-based interactive map that visualizes earthquake data from the past month. This project utilizes **Leaflet.js** for map rendering and **D3.js** for fetching GeoJSON earthquake data provided by the USGS (U.S. Geological Survey). 

Earthquakes are displayed as circle markers on the map, with:
- **Size** of the marker based on earthquake magnitude.
- **Color** of the marker based on earthquake depth.
- Interactive pop-ups for detailed earthquake information.

---

## Data Files

| File Name         | Description                                            |
|-------------------|--------------------------------------------------------|
| `index.html`      | The main HTML file that loads the map and references CSS and JS files. |
| `style.css`       | CSS file for styling the map layout and full-page design. |
| `logic.js`        | JavaScript file containing Leaflet setup, data fetch, and visualization logic. |

---

## Features

- **Dynamic Map Visualization**:
  - Displays earthquake locations as interactive markers.
  - Marker size reflects the magnitude of the earthquake.
  - Marker color reflects the earthquake depth.

- **Interactive Popups**:
  - Provides additional information, including location, magnitude, and depth.

- **Legend**:
  - A map legend explains the color coding for earthquake depths.

- **Live Data**:
  - Fetches real-time earthquake data from the **USGS GeoJSON API**.

---

## Installation

1. **Prerequisites**:
- Modern Web Browser (e.g., Chrome, Firefox, Edge)
- Internet Connection

2. **Setup**:
- Clone this repository or download the project files.
---

## Results

The dashboard visually represents earthquake data with:
* Larger circles for higher magnitude earthquakes.
* Color-coded depths to distinguish shallow and deep earthquakes.
* Real-time updates from USGS for recent earthquakes.
---

## File Structure

earthquake-visualization/
│
├── index.html           # Main HTML file
├── static/
│   ├── css/
│   │   └── style.css    # Custom CSS styling
│   └── js/
│       └── logic.js     # JavaScript code for map and data visualization
└── README.md            # Project documentation

---

## Author

**Kendall Burkett**  
https://github.com/KendallBurkett?tab=repositories
 
kbz1987@icloud.com