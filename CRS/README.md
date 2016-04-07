Custom Coordinate Reference System Definitions
==============================================
*CC-SA-BY 2016 - Miguel Sevilla-Callejo*

## Proj4 Defintions
Links:
- [PROJ.4 - Frequently Asked Questions](http://proj.maptools.org/faq.html)
- [Map projection - Wikipedia](https://en.wikipedia.org/wiki/Map_projection)
- [Map Projection Transitions - jasondavies.com](https://www.jasondavies.com/maps/transition/)
- [Map Projections - Quadibloc](http://www.quadibloc.com/maps/mapint.htm)


## World projections

### Mollweide
	+proj=moll +lon_0=Central Meridian
        +x_0=False Easting
        +y_0=False Northing

	+proj=moll +lon_0=0
    	+x_0=0 +y_0=0 +ellps=WGS84 +datum=WGS84 +units=m +no_defs

### Robinson
	+proj=robin
    	+lon_0=0
        +x_0=0
        +y_0=0
        +ellps=WGS84 +datum=WGS84 +units=m +no_defs

### Orthographic
	+proj=ortho +lat_0=Latitude at projection center 
         +lon_0=Longitude at projection center
         +x_0=False Easting
         +y_0=False Northing

	+proj=ortho +lat_0=0
    	+lon_0=0
        +x_0=0 +y_0=0
        +ellps=WGS84
        +datum=WGS84
        +units=m +no_defs

### Sinusoidal
	+proj=sinu +lon_0=Longitude at projection center
    	+x_0=False Easting
    	+y_0=False Northing

	+proj=sinu
    	+lon_0=0 +x_0=0
        +y_0=0
        +ellps=WGS84
        +datum=WGS84
        +units=m +no_defs

### Gnomonic (meridian)
	+proj=gnom
    	+lat_0=0
        +lon_0=0
        +x_0=0
        +y_0=0

### PseudoMercator --> "Google Mercator"
	+proj=merc
    +a=6378137 +b=6378137 +lat_ts=0.0 +lon_0=0.0
    +x_0=0.0 +y_0=0 
    +k=1.0 +units=m +nadgrids=@null +wktext  +no_defs

## Regional projections

### European Lambert

Personal1 - derivada del mapa de paisajes de Europa (LANMAP2)

	+proj=aea
    	+lat_1=32.5 +lat_2=45 +lat_0=51.4 +lon_0=0
        +x_0=0 +y_0=0
        +ellps=WGS72 +towgs84=0,0,4.5,0,0,0.554,0.2263
        +units=m +no_defs

## Personal projections

### ED50 / UTM 30 ES - EPSG23030 + nadgrid
	+proj=utm +zone=30 +ellps=intl +nadgrids=~/PENR2009.gsb +units=m +no_defs +wktext