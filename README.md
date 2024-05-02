# Mercury Maps
## What is it for?
 - Generate a bunch of points of interest on a map
 - Create routes if needed on the map
 - Simple util tool for geographic info.

## TODO
- [ ] Automated way to get `lat long coords` of any location text. <code>_Need a way to identify from multiple possibilities_</code>
- [ ] Separate points of interest as tier 1 (Actual points of interests, interactable) and route (Part of some route).
- [ ] Display all the points.

## Approach
1. Lat-long coord grabber: `Maps api` else `browser extension`.
2. Store data: `csv` or `json`, JSON is probably better as it adds possibility to add extra details per position. 
3. Generate map: `Folium` or some other map building python lib.