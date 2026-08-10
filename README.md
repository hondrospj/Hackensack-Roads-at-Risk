# Hackensack Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Hackensack municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01378570, Hackensack
- PETSS / NOAA station: 8530278
- NAVD88 thresholds: 4.28 ft minor, 5.58 ft moderate, 7.08 ft major
- MLLW thresholds: 7.8 ft minor, 9.1 ft moderate, 10.6 ft major
- MLLW = NAVD88 + 3.52 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Hackensack boundary at 5.1-foot adaptive resolution.
