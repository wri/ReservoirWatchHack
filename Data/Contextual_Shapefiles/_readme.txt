Author: Samantha Kuzma
Date: 2021/05/03
Version: 01


Data:
1. Bangalore.shp
Description: Administrative Level 3 boundary for Bangalore. GID_3 = IND.16.3.2_1
Source: Database of Global Administrative Areas (GADM) version 3.6
	https://gadm.org/index.html
Citation: GADM. 2018. GADM Database of Global Administrative Areas 3.6 (version 3.6).Global Administrative Areas. https://gadm.org/download_world.html.


2. hydrobasin6_Bangalore_clip
Description: Selected catchments that hydrologically link the water supply reservoirs to Bangalore.
	     This was done using the HYBAS_ID and NEXT_DOWN fields. 
	     These catchments can be connected to the Aqueduct Water Risk information using the PFAF_ID.
Source: WWF HydroSHEDS (hybas_as_lev06_v1c.zip)
	https://www.hydrosheds.org/downloads
Citation: Lehner, B., Grill G. (2013): Global river hydrography and network routing: baseline data and new approaches to study the world’s large river systems. Hydrological Processes, 27(15): 2171–2186. Data is available at www.hydrosheds.org.


3. hydrobasin6_India_clip
Description: All hydrobasin 6 catchments that at least partially fall within India's country borders.
Source: WWF HydroSHEDS (hybas_as_lev06_v1c.zip)
	https://www.hydrosheds.org/downloads
Citation: Lehner, B., Grill G. (2013): Global river hydrography and network routing: baseline data and new approaches to study the world’s large river systems. Hydrological Processes, 27(15): 2171–2186. Data is available at www.hydrosheds.org.


4. reservoirs.shp
Description: Hackathon's highlighted reservoirs. These supply Bangalore with water.
	     Note: The Harangi and Yagachi polygons were not included in the GRanD data. 
	           These were digitized by WRI using water body outlines.  
Source: Global Reservoir and Dam (GRandD) v1
https://sedac.ciesin.columbia.edu/data/set/grand-v1-reservoirs-rev01/data-download
Citation: Lehner, B., C. Reidy Liermann, C. Revenga, C. Vorosmarty, B. Fekete, P. Crouzet, P. Doll, M. Endejan, K. Frenken, J. Magome, C. Nilsson, J.C. Robertson, R. Rodel, N. Sindorf, and D. Wisser. 2011. Global Reservoir and Dam Database, Version 1 (GRanDv1): Reservoirs, Revision 01. Palisades, NY: NASA Socioeconomic Data and Applications Center (SEDAC). https://doi.org/10.7927/H4HH6H08. Accessed 03 05 2021