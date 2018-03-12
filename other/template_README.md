## Table Metadata ##

This is an informal set of metadata for 2D and 3D models produced from
archaeological line drawings via the
MicroPasts crowdsourcing web platform (http://crowdsourced.micropasts.org).

### General Information ###

This model is based on a line drawing originally made by Penny
Copeland for the University of Southampton's *Roman Amphorae: a digital resource*
(http://archaeologydataservice.ac.uk/archives/view/amphora_ahrb_2005/). This
drawing has been digitised as vector polygons by two or more
contributors via MicroPasts and then post-processed to create clean 2d
polygon and 3d (mesh) models.

This particular drawing belongs to the 'AAAA'
Roman amphora type, and was re-drawn for the above web resource as
BBBB, after a depiction in CCCC (see http://archaeologydataservice.ac.uk/archives/view/amphora_ahrb_2005/reference_all.cfm)

### Available Data ###

The directory enclosing this README should contain a /userchecks sub-directory
containing the original line drawing in jpeg format, pdf plots of each
contributor's digitised data, and a csv table containing a numerical
summary of each contribution. These files are all meant for quality
control purposes, enabling sensible choices for the 2d model-build
below.

Another sub-directory named /build2d should contain two vector polygon
datasets in ESRI shapefile format. The first 'forBlender' is only meant
as input for the 3d model-building Blender script, whilst the second
'2Dpoly' is a clean final version that can be used for a variety fo
plotting, measuring and outline analysis purposes. A .pdf in this
sub-directory offers a quick graphical summary of the clean 2d model.

A third and final sub-directory named /blend3d should contain a .blend
format file which is the main 3d model, alongside separate and
manifold mesh versions in .obj format. A .png in this sub-directory offers a quick graphical summary of the rendered 3d model.

### Licensing and Acknowledgments ###

License: CC0

Original Drawing: Penny Copeland
Crowd-sourcing app: Andrew Bevan
Crowd-sourcing framework: Pybossa
Crowd-sourcing Contributors: DDDD (where * indicates contributions that were prioritised in post-processing)
Post-Processing Scripts: Andrew Bevan, Tom Haines
UserChecks, 2dBuild, 3dBlend: EEEE

### Processing and Quality Assessment ###
This model was built online via the MicroPasts crowd-sourcing platform and thereafter offline via a combination of scripted procedures in R and Blender.

The handle style is only approximate as the section has been automatically 'lofted' along the curve of the handle profile. Otherwise, there are no known problems with these models.
