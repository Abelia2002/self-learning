# gis
## R Packages for GIS

| Package | Purpose |
|--------|---------|
| `sf` | Reading, writing, and manipulating spatial data we can focus on our different area |
| `leaflet` | Creating interactive web maps and not good for output but good for discussion|
| `ggplot2 + geom_sf()` | Creating static spatial visualizations good for output in report |
| `tmap` | Thematic map visualizations (static or interactive) |
| `tidygeocoder` | Transformation between the postal code and long/latitude |


## 📂 Typical Workflow

1. Load spatial data (e.g. shapefile, geojson)
3. Clean and transform data (`st_transform()`, `mutate()`)
4. Join with external data (e.g. postal code frequency)
5. Visualize using leaflet or ggplot2
6. Export final map or report

## package with details

### shapefile
- background or base layer or some FSA areasa and districts
- join the data like you can add some people with same FSA together
- analysis unit
- which standard we use depends on the we needs we can choose multiple choices based on the questions
### geojson ( not so familiar )
- more readable
- more used in interactive map
### leaflet

| Feature | Description |
|---------|-------------|
|  `addTiles()` | Add a base map |
|  `addCircles()`, `addMarkers()` | Add points or coordinates with tooltips |
|  `addPolygons()` | Show regions like FSA zones |
|  `popup`, `label` | Add interactive information on hover or click |


## sta313 reflection
why our interactive map often failed in sta 313 final project: because we tried to output the leaflet as pdf in R, so 
that is not good way to show the map. For the interactive map the html is the best way to show it and good for our discussion but 
for the final report the static map works better.

## heatmap or choropleth
choropleth needs boundry so that we can compare different areas and its frequence but for the heatmap we can only see the whole trend.
we can only see which area has the most frequency.



