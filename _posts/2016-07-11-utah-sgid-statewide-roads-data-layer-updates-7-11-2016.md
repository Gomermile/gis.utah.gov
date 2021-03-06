---
layout: post
status: publish
published: true
title: 'Utah SGID Statewide Roads Data Layer Updates 7/11/2016'
author:
  display_name: Greg Bunce
  email: gbunce@utah.gov
date: 2016-07-11 22:09:10
categories:
- Data
- Featured
tags:
- SDE
- sgid
- Geocoding
- Data
- utah
- gis
- map
- mapping
- Cartography
- Roads
- Streets
- location
- address
- dataset
- download
- agrc
- layer
- shapefile
- geodatabase
- shp
- gdb
- lyr
- digital
- geographic
- information
- database
- state
- statewide
- centerlines
- vector
- arcgis
---

Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the [Utah SGID ArcSDE database server]({{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}).

The updated Roads data is also available as shapefiles and file geodatabase files for download on the <a href="ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/">SGID FTP site</a>.

Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.

The following highlights were updated:

#### County Updates:

 - **Cache:** Received centerline update 06/10/2016: added new roads, road name and address range changes since last update on 01/25/2016; geocoding improvements
 - **Salt Lake:** Received VECC's centerline update 06/20/2016: added new roads, road name and address range changes since last update 03/21/2016; geocoding improvements
 - **Summit:** Received centerline update 02/17/2016: added new roads, road name and address range changes since last update 04/01/2015; geocoding improvements

#### Blue Stakes of Utah Feedback:

 - **Box Elder:** geocoding improvements
 - **Morgan:** geocoding improvements
 - **Wasatch** geocoding improvements

#### Granite School District Feedback:

 - **Salt Lake:** geocoding improvements
 
#### Box Elder County Feedback:

  - **Box Elder:** geocoding improvements
 

#### UDOT Route System:

 - The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated
 - The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated
