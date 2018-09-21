"# dartrashleaflet"

#TODO:

- Load the GeoJSON from a file, not embedded within the html.
- Don't load all of the GeoJSON; only load the points within the browser window
- Don't try to load all of the GeoJSON when zoomed out too far (scale-dependent rendering)
  - At low zoom levels (for example showing the whole city), we should actually see a reduced-resolution image of the trash. 
- Figure out how to change the default pins to small circles, which are bigger or smaller depending on the size of the trash pile (the field "trash_size" in the data).
  - But keep the popup behaviour
- Figure out how to have the other data (the attributes of the trash pile) alongside the photo
- Make the photo clickable to view in full screen

