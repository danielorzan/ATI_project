Room schema
### __EFMIGRATIONSHISTORY
|COLUMN|DESCRIPTION|
| :-: | :-:|
| MigrationId | |
| ProductVersion | |
### SPATIAL_REF_SYS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| srid | |
| auth_name | |
| auth_srid | |
| ref_sys_name | |
| proj4text | |
| srtext | |
### SPATIALITE_HISTORY
|COLUMN|DESCRIPTION|
| :-: | :-:|
| event_id | |
| table_name | |
| geometry_column | |
| event | |
| timestamp | |
| ver_sqlite | |
| ver_splite | |
### SQLITE_SEQUENCE
|COLUMN|DESCRIPTION|
| :-: | :-:|
| name | |
| seq | |
### GEOMETRY_COLUMNS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| f_table_name | |
| f_geometry_column | |
| geometry_type | |
| coord_dimension | |
| srid | |
| spatial_index_enabled | |
### SPATIAL_REF_SYS_AUX
|COLUMN|DESCRIPTION|
| :-: | :-:|
| srid | |
| is_geographic | |
| has_flipped_axes | |
| spheroid | |
| prime_meridian | |
| datum | |
| projection | |
| unit | |
| axis_1_name | |
| axis_1_orientation | |
| axis_2_name | |
| axis_2_orientation | |
### VIEWS_GEOMETRY_COLUMNS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| view_name | |
| view_geometry | |
| view_rowid | |
| f_table_name | |
| f_geometry_column | |
| read_only | |
### VIRTS_GEOMETRY_COLUMNS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| virt_name | |
| virt_geometry | |
| geometry_type | |
| coord_dimension | |
| srid | |
### GEOMETRY_COLUMNS_STATISTICS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| f_table_name | |
| f_geometry_column | |
| last_verified | |
| row_count | |
| extent_min_x | |
| extent_min_y | |
| extent_max_x | |
| extent_max_y | |
### VIEWS_GEOMETRY_COLUMNS_STATISTICS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| view_name | |
| view_geometry | |
| last_verified | |
| row_count | |
| extent_min_x | |
| extent_min_y | |
| extent_max_x | |
| extent_max_y | |
### VIRTS_GEOMETRY_COLUMNS_STATISTICS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| virt_name | |
| virt_geometry | |
| last_verified | |
| row_count | |
| extent_min_x | |
| extent_min_y | |
| extent_max_x | |
| extent_max_y | |
### GEOMETRY_COLUMNS_FIELD_INFOS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| f_table_name | |
| f_geometry_column | |
| ordinal | |
| column_name | |
| null_values | |
| integer_values | |
| double_values | |
| text_values | |
| blob_values | |
| max_size | |
| integer_min | |
| integer_max | |
| double_min | |
| double_max | |
### VIEWS_GEOMETRY_COLUMNS_FIELD_INFOS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| view_name | |
| view_geometry | |
| ordinal | |
| column_name | |
| null_values | |
| integer_values | |
| double_values | |
| text_values | |
| blob_values | |
| max_size | |
| integer_min | |
| integer_max | |
| double_min | |
| double_max | |
### VIRTS_GEOMETRY_COLUMNS_FIELD_INFOS
|COLUMN|DESCRIPTION|
| :-: | :-:|
| virt_name | |
| virt_geometry | |
| ordinal | |
| column_name | |
| null_values | |
| integer_values | |
| double_values | |
| text_values | |
| blob_values | |
| max_size | |
| integer_min | |
| integer_max | |
| double_min | |
| double_max | |
### GEOMETRY_COLUMNS_TIME
|COLUMN|DESCRIPTION|
| :-: | :-:|
| f_table_name | |
| f_geometry_column | |
| last_insert | |
| last_update | |
| last_delete | |
### GEOMETRY_COLUMNS_AUTH
|COLUMN|DESCRIPTION|
| :-: | :-:|
| f_table_name | |
| f_geometry_column | |
| read_only | |
| hidden | |
### VIEWS_GEOMETRY_COLUMNS_AUTH
|COLUMN|DESCRIPTION|
| :-: | :-:|
| view_name | |
| view_geometry | |
| hidden | |
### VIRTS_GEOMETRY_COLUMNS_AUTH
|COLUMN|DESCRIPTION|
| :-: | :-:|
| virt_name | |
| virt_geometry | |
| hidden | |
### SQL_STATEMENTS_LOG
|COLUMN|DESCRIPTION|
| :-: | :-:|
| id | |
| time_start | |
| time_end | |
| user_agent | |
| sql_statement | |
| success | |
| error_cause | |
### SPATIALINDEX
|COLUMN|DESCRIPTION|
| :-: | :-:|
### ELEMENTARYGEOMETRIES
|COLUMN|DESCRIPTION|
| :-: | :-:|
### PROJECT
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ProjectId | |
| Phase | |
### DOCUMENT
|COLUMN|DESCRIPTION|
| :-: | :-:|
| DocumentId | |
| FileBytes | |
| IsWorkshared | |
| Latitude | |
| Longitude | |
| Name | |
| Path | |
| ProjectId | |
| ProjectName | |
| ProjectNumber | |
| RevitBuild | |
| RevitVersion | |
| UploadDate | |
| Username | |
| VersionGuid | |
| WorksharedPath | |
| Discipline | |
| Hash | |
### DOCUMENTPARAMETER
|COLUMN|DESCRIPTION|
| :-: | :-:|
| DocumentParameterId | |
| DocumentId | |
| Name | |
| RevitId | |
| SharedGuid | |
| Value | |
| ValueType | |
### ELEMENT
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ElementId | |
| Category | |
| DocumentId | |
| Name | |
| RevitId | |
| RevitUniqueId | |
| Type | |
| LocationGeoJson | |
| Location | |
| IsInstance | |
| Mesh | |
### WORKSET
|COLUMN|DESCRIPTION|
| :-: | :-:|
| WorksetId | |
| DocumentId | |
| Kind | |
| Name | |
| RevitId | |
| RevitUniqueId | |
### ELEMENTPARAMETERINTEGER
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ElementParameterIntegerId | |
| ElementId | |
| Name | |
| RevitId | |
| SharedGuid | |
| Value | |
### ELEMENTPARAMETERNUMBER
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ElementParameterNumberId | |
| ElementId | |
| Name | |
| RevitId | |
| SharedGuid | |
| Value | |
### ELEMENTPARAMETERREVITID
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ElementParameterRevitIdId | |
| ElementId | |
| Name | |
| RevitId | |
| SharedGuid | |
| Value | |
### ELEMENTPARAMETERTEXT
|COLUMN|DESCRIPTION|
| :-: | :-:|
| ElementParameterTextId | |
| ElementId | |
| Name | |
| RevitId | |
| SharedGuid | |
| Value | |
