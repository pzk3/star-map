# star-map
A efficient, locally hosted map of the closest 1000 stars to the solar system within 500 light years. 
<img width="1908" height="830" alt="image" src="https://github.com/user-attachments/assets/03149ac5-c25f-40bf-8341-1c2f383b5f53" />
<img width="1908" height="831" alt="image" src="https://github.com/user-attachments/assets/737a8283-71f7-46f9-82b8-632c2c733315" />

## Features
 
- **1,001 real stars** sourced from the HYG stellar database (v4.2)
- **True 3D positions** — stars are placed using their actual XYZ cartesian coordinates, not just RA/Dec projections. Stars surround Sol in all directions.
- **Logarithmic depth scaling** — nearby stars aren't crushed against the origin; distance is compressed so the full neighbourhood is explorable at once
- **Vertical depth stems** — faint lines drop from each star to the galactic plane, making the third dimension immediately readable
- **Per-star colour** derived from the B-V colour index column — each star is its actual photometric colour (deep blue O-stars through orange-red M-dwarfs)
- **Distance rings** at 5, 10, 20, 30, 50, 100, 200, and 500 LY
- **Click any star** to fly to it — camera positions itself on the far side so deep space is the backdrop, not the Sun
- **Search** by proper name, Bayer designation, Gliese ID, or constellation
- **Filter panel** — slice by distance, apparent magnitude, and spectral class
- **Detail panel** — full data readout per star: distance, luminosity, spectrum, colour index, proper motion, radial velocity, catalogue IDs

---

## Controls
 
| Input | Action |
|---|---|
| **Drag** | Orbit camera |
| **Scroll** | Zoom in / out |
| **Right-drag** | Pan |
| **Click star** | Select & fly to it |
| **R** | Reset view |
| **F** | Fullscreen |
| **Esc** | Close detail panel |
 
---

Data is sourced from a snippet of the [HYG database](https://www.astronexus.com/projects/hyg) under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/) Snippet was changed from the original by only keeping the 1000 closest stars rather than the entire database.
