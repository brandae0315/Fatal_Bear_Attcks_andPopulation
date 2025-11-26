# Fatal Bear Attacks 2000–2025

## Project Overview
This project explores the intersection of human–wildlife conflict and ecological data by mapping fatal bear attacks across North America from 2000–2025. The interactive visualization combines incident locations with state-level bear population estimates to provide a clearer picture of where risks are concentrated and how they relate to bear distribution. By integrating multiple data sources, the map highlights both the rarity and geographic clustering of fatal encounters, while also emphasizing the importance of understanding bear ecology in conservation and public safety contexts.

The map is designed to be both informative and accessible. Users can zoom and pan to explore regions, click on states to reveal bear population counts, and interpret attack patterns through custom icons for different bear species. Choropleth shading adds another layer of insight, showing relative population densities. Together, these features create a map for education and awareness about human–bear interactions.


## Features
- **Interactive Map**: Built with Leaflet, allowing users to explore attack locations and bear population densities.
- **Custom Icons**: Distinguish between Brown, Black, and Polar bear incidents using Font Awesome paw markers.
- **Choropleth Layer**: Displays bear population per state with graduated color scales for easy comparison.
- **Popups & Legend**: Clickable states reveal bear population counts; legend clarifies symbology.

## Libraries Used
- [Leaflet](https://leafletjs.com/) for mapping
- [Leaflet-AJAX](https://github.com/calvinmetcalf/leaflet-ajax) for GeoJSON integration
- [Chroma.js](https://gka.github.io/chroma.js/) for color scales
- jQuery for dynamic styling

## Data Sources
- [ArcGIS Bear Attacks Map](https://www.arcgis.com/apps/mapviewer/index.html?webmap=8f8ecfe1854e4ca0a57b5da6e54e211b)  
- [Black Bear Population by State](https://worldpopulationreview.com/state-rankings/black-bear-population-by-state)  
- [Grizzly Bear Population by State](https://worldpopulationreview.com/state-rankings/grizzly-bear-population-by-state)  
