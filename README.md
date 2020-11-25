## trans-Iapetus_2020

GPlates  files for replicating our continental reconstruction:

All continents are reconstructed in the paleomagnetic frame (004).

Reconstruction file: trans-Iapetus.rot

Coastline file: Coastline_trans-Iapetus.gpml

Input paleopole files for Gondwana (Plateid=701), Laurentia (Plateid=101), Baltica (Plateid=302) and Laurussia (Plateid=302): ex: poleCGond.shp (.dbf / .shx): Gondwanan paleopole centers poleEGond.shp (.dbf / .shx): Gondwanan paleopole error ellipses

APWP files for Gondwana (Plateid=701), Laurentia (Plateid=101), Baltica (Plateid=302) and Laurussia (Plateid=302): ex: rmSplpGond.shp (.dbf / .shx): Gondwanan running mean poles rmSpllGond.shp (.dbf / .shx): Gondwanan spline poles / curve

Three steps to show the early Paleozoic continental reconstructions:

Run GPlates, select 'File' > 'Open Project' > 'Pangea_Formation_Coastlines.prj' (all files will be loaded);

Select 'Reconstruction' > 'Specify Anchored Plate ID' > type '4' (paleomagnetic frame);

Select 'Reconstruction' > 'Reconstruction to Time' > type an integer between 440 and 510 Ma.
