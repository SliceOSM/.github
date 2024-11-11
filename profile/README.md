SliceOSM is a web downloads portal for fresh [OpenStreetMap](https://openstreetmap.org) data. 

If you've just edited OpenStreetMap, a new [OSM PBF](https://wiki.openstreetmap.org/wiki/PBF_Format) slice reflects those changes up to the minute.

Create a slice for any custom bounding box, GeoJSON polygon or multipolygon area.

SliceOSM is an [OpenStreetMap US Community Project](https://openstreetmap.us/our-work/community-charter-projects/).

## Components

* [OSM Express](https://github.com/bdon/OSMExpress) - the database that spatially indexes and replicates the OpenStreetMap planet data.
* [sliceosm-api](https://github.com/SliceOSM/sliceosm-api) - a lightweight web server to access an OSM Express database.
* [sliceosm-frontend](https://github.com/SliceOSM/sliceosm-frontend) - A single-page app for interacting with `sliceosm-api`.

## Alternatives

* [planet.openstreetmap.org](https://planet.openstreetmap.org) for the full planet PBF, updated weekly.
* [Geofabrik Downloads](https://download.geofabrik.de/) for PBFs of pre-selected areas updated once a day.
* [Overpass Ultra](http://overpass-ultra.us), [Overpass Turbo](https://overpass-turbo.eu) for GeoJSON downloads of minute-updated data, or data filtered only to certain tags. 


## Background

This project previously existed as **Protomaps Extracts** but has been migrated to OSMUS. It succeeds a long line of extract services including [migurski/Extractotron](https://github.com/migurski/Extractotron) and [Mapzen Extracts On Demand](https://www.mapzen.com/blog/metro-extracts-on-demand/).
