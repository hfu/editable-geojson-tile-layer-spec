# EditableGeoJSONTileLayer
## Basic spec
- should work with Leaflet 1.0 series
- overzooming enabled
- underzooming enabled with sensible default limit

## Heuristic optimization for existing vector tiles
- dynamic switch between canas and svg renderer based on heuristics for OSM vector tiles and GSI vector tiles
- it is for performance. yes, GeoJSON tiles need optimizations for performance

## Make it editable, to realize 'vector tiles which can take pull requests.'
- make it editable
- the result of the edit will be tilewise pull request.

By making the TileLayer editable and pull-requestable, the choice of GeoJSON over binary will be rationalized.
