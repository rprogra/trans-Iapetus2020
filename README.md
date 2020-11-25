## trans-Iapetus_2020

GPlates  files for replicating our continental reconstruction:

All continents are reconstructed in the paleomagnetic frame (004).

__Reconstruction file__: trans-Iapetus.rot

__Coastline file__: Coastline_trans-Iapetus.gpml

Input paleopole files for Gondwana (Plateid=701), Laurentia (Plateid=101), Baltica (Plateid=302) and Laurussia (Plateid=302): ex: poleCGond.shp (.dbf / .shx): Gondwanan paleopole centers poleEGond.shp (.dbf / .shx): Gondwanan paleopole error ellipses

APWP files for Gondwana (Plateid=701), Laurentia (Plateid=101), Baltica (Plateid=302) and Laurussia (Plateid=302): ex: rmSplpGond.shp (.dbf / .shx): Gondwanan running mean poles rmSpllGond.shp (.dbf / .shx): Gondwanan spline poles / curve

Three steps to show the early Paleozoic continental reconstructions:

Run GPlates, select 'File' > 'Open Project' > 'Pangea_Formation_Coastlines.prj' (all files will be loaded);

<li Select 'Reconstruction' > 'Specify Anchored Plate ID' > __type '4' (paleomagnetic frame)__;

<li Select 'Reconstruction' > 'Reconstruction to Time' > type an age between 440 and 510 Ma.
