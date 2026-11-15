# pathalgorithm

AI was used for parts of this code.

How to use:
python pathfind.py --start lon1 lat1 --end lon2 lat2
Saves all points in .json format

Optional parameters:
--plot: Plots the route using matplotlib in a window.
--margin-km: Margin around the line to load the map.
--slope-weight: multiplier for the slope cost calculation.
--clearance-m: How far to keep away from blocked terrain >20 degrees.
--out: prefix for lonlat.json (e.g path_lonlat.json)