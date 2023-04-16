# Satellite orbit plotting tools and projects

Poliastro plotter is used for pulling orbit parameters and plotting on online map. 

TLE to xxx tool is especially for transforming TLEs to more easily usable for in GIS tools
Fairly easy way to get specific TLEs is to use Space-Track https://www.space-track.org/#queryBuilder

There should be a few for each day, so it is convenient to filter by date

There Class TLE ordered by epoch
Filters 
Norad_Cat_id equal to the wanted satellite
Epoch greater than the low bound
Epoch lesser than the high bound

example query
https://www.space-track.org/basicspacedata/query/class/tle/NORAD_CAT_ID/43804/EPOCH/>2022-12-05 11:16:52,<2022-12-07 11:16:52/orderby/EPOCH asc/limit/100/emptyresult/show
