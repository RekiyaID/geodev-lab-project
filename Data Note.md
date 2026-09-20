# Data Note

# GRID# Nigeria Operational LGA
Source: https://data.grid3.org/datasets/GRID3::grid3-nga-operational-lga-boundaries/about
Downloaded Date (December 2020)
Columns: LGA_name (text), State_name (text)
No nulls in the LGA_name

## OSM roads, extracted via QuickOSM
-Query: Highways within the Kachia LGA extent
-Extracted date [Not seen]
-1825 line features
-113 point features
-Many of these features have no surface tags, which means the roads cannot be separated, they are all seen as generic
-Coverage looks good in built-up area, and surroundings

## CRS and Projections
-All sources arrived in ESPG 4326
Study Area: Kachia LGA, extracted from Grid3 LGA
-All layers clipped and then reprojected to ESPG:32632 (UTM 32N)
- Area check: Kachia LGA 4570 Km2 matches the published figure
working files in data/processed/, raw files untouched
