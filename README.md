# Lothian Birds
Python code for generating an html report using recent publicly available eBird data for specified region(s). Script queries the eBird API to get recent sightings and processes those to generate report of notable sightings (notable is either an uncommon species or high count for common birds, as set in species_config.yml).

Output report is accessible through GitHub pages at: https://pasimasa.github.io/lothianbirds

TODO:
1.  Parameterise the eBird region used to select records - options are config file or environment variable - the former is probably less complicated for consumers
2.  Parametrise the region name and sub heading text in the main website and the observatiuon count graphic
3.  Provide more detailed instructions on how to clone the repositiory when using it for a new region including resetting the observation counts
4.  Rename the repository so that the name is not specific to Lothian - perhaps eBirdRecentSightings?
