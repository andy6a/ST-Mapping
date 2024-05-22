# ST-Mapping
Sourcetracker mapping functions
All functions can require python 3.8 or greater.
All functions have an output name variable to add to the output name default is to add a "1" default.

# Functions
mapping_input:
takes in a larger mapping file, a column for SampleID, SourceSink, and Env. 
Also optional additions are a sink list and an added environmental column to add environments.

map_match_otu:
requires a mapping file and an otu file and filters the mapping file based upon matching id names

mapping_to_mapping:
takes in a mapping file, a list of environments to be dropped and a list of envs to change source to sink and sink to source

drop_items
requires a mapping file and a list of items to be dropped.

merge_env:
requires a mapping file and a list of environments with the first to be merge into
