Tables :
pv

	Columns :
		osm_objtype : OpenStreetMap object type - 'node' (points), 'way' (polygons and polylines), 'relation' (grouping to express real-world geographical relationships)
		osm_id : OpenStreetMap ID
		repd_id : Renewable Energy Planning Database ID
		repd_site_name : Renewable Energy Planning Database name for the site
		capacity_repd_MWp : Renewable Energy Planning Database Megawatt estimated peak capacity of PV panel
		capacity_osm_MWp : OpenStreetMap Megawatt estimated peak capacity of PV panel
		latitude : Latitude co-ordinate in degrees
		longitude : Longitude co-ordinate in degrees
		area_sqm : Area in square metres
		located : Mounting location of PV panel - 'ground', 'surface', 'roof', 'floating_pontoon', 'platform', 'wall', 'overground', 'outdoor' (some mislabelled as 'place', '76', '16', 'root', 'rood', 'rii', 'roof`', 'gound', 'yes', 'groundPendle'). None when location is not known.
		orientation : Cardinal direction for orientation of the PV panel (0 degrees = North)
		osm_power_type : OpenStreetMap power type for the PV panel - 'generator', 'plant'
		osm_tag_start_date : OpenStreetMap construction completion date
		num_modules : Number of PV modules at this location
		repd_status : Renewable Energy Planning Database status of PV panel - 'Application Submitted', 'Awaiting Construction', 'Under Construction', 'Operational'
		repd_operational_date : Renewable Energy Planning Database start date of operation
		old_repd_id : Renewable Energy Planning Database previous ID
		osm_cluster_id : OpenStreetMap Cluster ID
		repd_cluster_id : Renewable Energy Planning Database Cluster ID
		source_capacity : Source used to estimate PV panel capacity (free form text)
		source_obj : Source used to visualise PV site (free form text)
		match_rule : Rules to use when matching between datasets
