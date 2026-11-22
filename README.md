# Myrtle Beach Sea-Level Rise Modeling

**May 2020** · Myrtle Beach and coastal Horry County, South Carolina

This exploratory map shows a 2050 sea-level-rise scenario as interpreted in 2020. It puts the modeled flood extent in context with Myrtle Beach, Horry County, and building footprints.

[Open the interactive map](https://tom-shanks.github.io/MB-Flooding/). **Layers** toggles the flood raster, building footprints, administrative boundaries, and reference map. Enable an administrative or building layer and select a feature to inspect its attributes.

## Sources and methods

- The [original README revision](https://github.com/Tom-Shanks/MB-Flooding/blob/e4d85f2/README.md) cites Climate Central's South Carolina sea-level-rise report. [Climate Central's sea-level-rise program](https://www.climatecentral.org/sea-level-rise) provides publisher context. The original report URL could not be verified as a direct PDF.
- Tom Shanks assembled this mapping exercise and published the raster and vector layers. His [original portfolio](https://tom-shanks.github.io/) identifies SRTM elevation data and [OpenStreetMap](https://www.openstreetmap.org/copyright) footprints. OpenStreetMap contributors also provide the reference basemap. The original administrative-layer publisher and exact data vintages are undocumented.
- The [exported data](data/) contains the raster and vector layers used by the QGIS/qgis2web export. Leaflet supplies map interactions.

The archive does not record the elevation processing, vertical datum, water-height threshold, or model validation needed to reproduce the scenario. Use it as an example of terrain, scenario, and exposure layers published together. Consult current official flood products for planning or safety decisions.
