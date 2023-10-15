# MAP671-Final-Project

**Project Title:** Disappearance of the historic Clare Market District in London

(https://github.com/sking80226/MAP671-KingFinal-Project/blob/main/Maps/2%20-%20Clare%20Market%208000%20px.jpg)

**Information about data source:** The historic map image was taken from the “A New and Exact Plan of the City of London and Suburbs (1739)” map by Sutton Nicholls.  The map was accessed at: https://collections.britishart.yale.edu/catalog/tms:36381.  The modern building and highway overlay was built using Open Street Map queries on QGIS 3.22.28.

**Description of why map was created:**  I first learned of the existence of the historic Clare Market District through genealogical research. Clare Market was an actual market established in the 1600s by the second Earl of Clare in central London. The name was also used to identify the neighborhood surrounding the market. I had traced one of my Scottish ancestors from Edinburgh to London where he lived for a time prior to the family’s immigration to North America. They family was documented in an English census record which included the street on which they resided. After hours of searching through modern maps, I could not locate the street so I started digging into historical maps where I found the market location and the street my ancestors had lived on.  Both had been demolished in the early 1900s for the creation of the Kingsway highway and new construction which included an extension of the London School of Economics. Clare Market was not affected by the Great Fire of London (1666) so many of the structures in the area dated back to Elizabethan times. By the late 1800s the area was in disrepair and considered a slum which is likely why it was chosen for demolition.

**Steps taken to create map:** To create this map, I first found a legible historical map that showed the area if interest, Clare Market. I then took a clip of that map, converted it a JPG and georeferenced the historic map to a modern map of the city of London in QGIS 3.22.28. For the modern map, I used the ERSI Standard map tile, leaving it in the EPSG: 4326 CRS. Using the present-day map, I ran a Quick OSM query to create a layer showing a map of the modern highways in the area and ran another to map the modern buildings. Both layers were then overlayed on top of the georeferenced historic map to show how they now cover the historic Clare Market neighborhood and market area. Once the layers were set, I then updated the project CRS to ESRI:102400.

**Active link to final index.html page: https://sking80226.github.io/MAP671-KingFinal-Project/

Embedded Images:

Image of projection of original data:

Image of projection of final data:
**
