# Building a map for a non-profit organization

I created a custom Google Map for New Sun Rising (NSR), an intermediary non-profit in Millvale, Pennsylvania. I actually work for NSR now, but since they have maps already, I created this for fun. [Here](https://docs.google.com/document/d/1HbKzIMSCzOUv8-vX3oL8kaNcIB31RyMy9U5IzevRiEI/edit?usp=sharing) is the one-page bid for the initial estimate for Phase 1 requirements


I used [Canva's Color Generator](https://www.canva.com/colors/color-palette-generator/) to create a color paltette for the map I wanted to create. In addition to the color palette provided below, I added an off-white color with HEX code #F2F2F2. Here is the color palette that I used to create this map:

![Map with color palette](map-ss.png)

Here is a lookup table that references relevant features and their coresponding colors on the maps below: 
| Feature Type | Element Type | Color from palette (HEX code) |
|--------------|-------------------|--------------------|
| All          | Labels/Text fill  |     #000000        |
| All          | Geometry          |     #EC883D        |
| Country      | Stroke            |     #FAE3D1        |
| Province     | Stroke            |     #FAE3D1        | 
| Land Parcel  | Lables/Text fill  |     #000000        |                    
| Landscape    | Stroke            |     #F2F2F2        |
| Natural      | Geometry          |     #F4C694        |
| Points of Interest (POI)| Labels/Text fill | #000000  |
| POI Park     | Fill              |     #F2F2F2        |
| POI Park     | Labels/Text fill  |     #000000        |
| Transit      | Labels/Text fill  |     #000000        |
| Transit/Line | Labels/Text fill  |     #000000        |
| Transit/Station  | Labels/Text fill  |     #000000    |
| Road        |  Geometry         |     #F2F2F2        |
| Road/Highway|  Geometry         |     #FAE3D1        |
| Road/Highway|  Stroke           |     #FAE3D1        |
| Road/Highway|  Label/Text fill  |     #000000        |
| Water       |  Geometry        |      #FAE3D1         |
| Water       |  Label/Text fill |      #000000         |






Here is the map that I created using the color palette above: 
Access the map's JSON code [here](map.json)


# 1 - Zoomed out view of Pittsburgh
![Pittsburgh](pghmap-ss.png)


# 2 - Zoomed in view of Millvale, Pennsylvania (Location of New Sun Rising)
![Millvale](millvalemap.png)

# 3 - View of Frick and Schenley Park in Pittsburgh

![Parks](parks.png)
