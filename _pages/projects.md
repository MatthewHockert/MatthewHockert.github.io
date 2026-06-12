---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
nav: true
---

### [Parking Near Transit in St. Paul: An Interactive Map](/files/maps/stpaul_transit_parking.html)
How much land within a 10-minute walk of high-frequency transit is consumed by parking lots — and what would a land value tax do about it? This interactive map routes 800 m walk sheds along the street network from all 103 METRO light rail and BRT stops in St. Paul, overlays OpenStreetMap parking lot footprints shaded by underlying land value per acre, and reports per-line outcomes under a revenue-neutral 4:1 split-rate property tax. Along the Green Line, one in six acres of taxable land within a short walk of a station is surface parking. Built with parcel data from Ramsey County, GTFS from Metro Transit, and OSM walking networks (Python: geopandas, osmnx, folium). [Explore the map →](/files/maps/stpaul_transit_parking.html)

### [When to Run](https://github.com/MatthewHockert/when_to_run)
A Python-based command-line tool that tells you the best time of day to go for a run, based on weather forecasts, run type, and optional city input. Pulls data from WeatherAPI and OpenStreetMap’s Nominatim geocoder.