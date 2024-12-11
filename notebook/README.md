# metadata-json2netcdf
This script is indented to create an empty netCDF file with the comtomized metadata info.  
From predefined metadata templates in Json, users could add and/or remove the attributes 
and populate/modify the attribute values as needed. Five predefined templates are provided 
in /smpl subdirectory, including:  
  1. point_mooring_template.json
  2. profile_ctd_template.json
  3. profile_sonde_template.json
  4. satellite_l2_template.json
  5. satellite_L3_L4_template.json
  6. trajectory_drifter_template.json

The script will output the updated metadata in both netCDF and Json files. The new json file
can be used as input iteratively. 
