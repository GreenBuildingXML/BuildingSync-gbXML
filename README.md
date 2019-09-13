# BuildingSync®

[![Build Status](https://travis-ci.org/BuildingSync/schema.svg?branch=develop)](https://travis-ci.org/BuildingSync/schema)

BuildingSync® is a common schema for energy audit data that can be 
utilized by different software and databases involved in the energy 
audit process. It allows data to be more easily aggregated, compared 
and exchanged between different databases and software tools. This 
streamlines the energy audit process, improving the value of the data
and facilitating achievement of greater energy efficiency.

The schema is developed by a National Renewable Energy Laboratory 
(NREL) led working group. Working group participants included industry 
partners, national laboratories, and industry organizations.


### Green Button Connect Schema Referencing

This version of BuildingSync references the GBC schema to allow GBC-style meter data to be present in a BuildingSync XML file.  For proper functioning, you must download a local copy of all schemas referenced:

* Green Building XML - [link](http://www.gbxml.org/Schema_Current_GreenBuildingXML_gbXML)
* Green Button Connect - [link](https://naesb.org//copyright/espi.xsd)
* Atom (referenced by the GBC schema) - [link](https://github.com/GreenButtonAlliance/OpenESPI-Common-java/blob/master/etc/atom.xsd)

Save those files to a directory of your choice, then open BuildingSync.xsd, inspect the `<import>` tags, and make sure the path/filenames to the schemas are correct.

--\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

In the /examples folder, there is one new file: 

`GBC_externalreference_meterdata.xml`

This is a basic mockup of a BuildingSync file with GBC meter reading data added to it.  The BuildingSync schema can be inspected for what GBC elements are allowed and where.
