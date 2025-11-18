# Amphan-Flood-Mapping-Khulna-Bangladesh
Objective:
To rapidly assess and quantify the spatial extent of flood inundation in the vulnerable Khulna district of Bangladesh, caused by the catastrophic storm surge of Cyclone Amphan in May 2020. The primary goal was to distinguish newly flooded agricultural and residential land from permanent water bodies to aid in immediate disaster response.

Data Acquisition:
This analysis leveraged Sentinel-1 C-Band SAR imagery from the Copernicus program. Key scenes were selected from a "before" period (April 25 - May 15, 2020) to establish a baseline, and an "after" period (May 16 - June 5, 2020) capturing the impact immediately following Amphan's landfall on May 20th. Auxiliary data from the JRC Global Surface Water and WWF HydroSHEDS DEM were used to refine the results.

Data Processing & Analysis:
Pre-processing: Sentinel-1 data (VH polarization) was processed in Google Earth Engine, applying a Refined Lee speckle filter to enhance image quality.
Change Detection: A ratio-based algorithm identified areas where radar backscatter significantly increased after the cyclone, a key indicator of surface flooding. An initial threshold was set to highlight these changes.
Impact Refinement: The raw flood map was critically refined by:
Removing Permanent Water: Using the JRC dataset to mask out rivers and lakes, ensuring the map showed only new flooding.
Eliminating Implausible Areas: Using slope data to exclude hilly terrain where floodwater cannot accumulate.
Reducing Noise: Filtering out small, isolated pixels to focus on large, contiguous flood-affected zones.

Potential Usage and Impact:
In the immediate aftermath of a super-cyclone like Amphan, which caused a massive storm surge and breached embankments in coastal Bangladesh, this rapid flood map serves as a vital tool for emergency services. It can direct rescue operations, identify the worst-hit communities, assess damage to agriculture (a key livelihood in Khulna), and inform the allocation of aid and resources for recovery, helping to save lives and livelihood
