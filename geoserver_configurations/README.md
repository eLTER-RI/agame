# AGAME project
## GeoServer configurations
https://www.umweltbundesamt.at/en/services/agame

- The .properties file of each layer needs to be modified and get an extra line that says "TimeAttribute=ingestion"
- The indexer.properties tells GeoServer that datetime information is in the filename
- The timeregex.properties tells GeoServer how to extract date information from the geotiff filenames (the last 8 characters contain the date)
- agame_legend.png and agame_legend.xcf provide the legend graphic used for the GPP layers on GeoServer
- gpp_grey_to_green.sld contains the SLD used to style the GPP layers on Geoserver

November 2024
