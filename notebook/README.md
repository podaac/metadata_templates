# meta-json2netcdf
This script is intended to create an empty netCDF file with customized internal CF/ACDD metadata.  
From predefined metadata templates in JSON, users can add or remove the attributes 
and populate/modify the attribute values as needed. Five predefined templates are provided:
in ./smpl subdirectory, including: 

  1. point_mooring_template.json
  2. profile_ctd_template.json
  3. profile_sonde_template.json
  4. satellite_l2_template.json
  5. satellite_L3_L4_template.json
  6. trajectory_drifter_template.json

The script will output the updated metadata as both netCDF and JSON files. The new JSON file
can be used as an input to futher iterate its contents. 
