# geocovid

# Visualizing the Geospatiotemporal Spread of the Pandemic

Displaying COVID-19 deaths per country per day on a rotating 3D Earth.

An animation displays on a 3D Earth the total number of deaths for each day. They are represented in log scale as cones positionned on capital's locations of each country. During the animation, the 3D Earth is rotating around its own axis eastward to enable the user to see the spread of the pandemic. The speed of the rotation is not related to the speed of Earth's rotation.

The outcome figure itself intends to look like the coronavirus as a sphere with spikes.

Data sources:

- COVID data per country + ISO 3 codes and per day from **Our World in Data**, see: https://ourworldindata.org/coronavirus-source-data
- Countries + ISO 2 and 3 codes from **GeoNames**, see: https://www.geonames.org/countries/
- Capitals + ISO 2 codes and latitude + longitude from **GeoNames**, see: http://download.geonames.org/export/dump/
- Coastlines shape file from **Natural Earth**, see: https://www.naturalearthdata.com/downloads/110m-physical-vectors/

Limitations of the data visualization:

- For large countries like China or the USA, displaying data per region would be more meaningful instead of data for the whole country and positionned on capital's location.
- The displayed 3D Earth uses a pure spherical model, it is not the actual shape of the Earth.
- The displayed 3D Earth is transparent, it might be opacified slightly to ease the interpretation of the graphic.
- The animation widget displays the number of days since the pandemic started, it might be switched to the actual date of the data.

Author: Francis Wolinski