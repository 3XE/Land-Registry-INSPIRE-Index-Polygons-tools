# Land Registry INSPIRE Index Polygons tools
Tools to make working with Land Registry INSPIRE Index Polygons easier.

## Land_Registry_Cadastral_Parcels.gfs
Fixes `ERROR 1: Failed to connect to 192.168.4.121 port 8080: No route to host` when attempting fancy imports using ogr2ogr

Usage on Linux:

    export GML_GFS_TEMPLATE=Land_Registry_Cadastral_Parcels.gfs
    ogr2ogr [...]    

Usage on Windows:

    SET GML_GFS_TEMPLATE=Land_Registry_Cadastral_Parcels.gfs
    ogr2ogr [...]  
