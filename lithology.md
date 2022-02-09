# Site selection based on surface lithology

Work in progress... 

Interactive viewer, clipped to only show quartzite dominated soils within the Pretoria Group: https://jdmwhite.users.earthengine.app/view/site-selection-quartz

Aspect is a derived product from the Shuttle Radar Topography Mission (SRTM). The categories used to convert degrees to cardinal directions are:

| Degrees  | Cardinal directions |
| ------------- | ------------- |
| 337.5 - 22.5 | N  |
| 22.5 - 67.5  | NE |
| 67.5 - 112.5  | E |
| 112.5 - 157.5 | SE  |
| 157.5 - 202.5 | S  |
| 202.5 - 247.5  | SW  |
| 247.5 - 292.5  | W  |
| 292.5 - 337.5  | NW  |

![pta_group_lith](https://user-images.githubusercontent.com/22145011/153000398-0957b9b5-1990-48ee-9beb-8342f2e2b465.png)
Figure 1. Simplified lithology descriptions of the Pretoria Group. The gray background indicates the grassland biome.

The surface lithology descriptions have been simplified from 16 down to 7 categories, based on the dominant lithology. Full descriptions are shown in the table below:

| Detailed categories  | Simplified categories |
| ------------- | ------------- |
| Andesite, conglomerate  | Andesite, conglomerate  |
| Basaltic andesite, minor felsite, pyroclastic rocks, arenite and hornfels  | Basaltic andesite  |
| Hornfels, quartzite, carbonate and chert  | CHornfels, quartzite |
| Metamorphosed mudstone and shale with minor quartzite, dolomite and chert | Meta. mudstone and shale  |
| Quartzite with minor shale and siltstone  | Quartzite  |
| Quartzite, feldspathic quartzite, arkose  | Quartzite  |
| Quartzite, minor shale  | Quartzite  |
| Quartzite, shale, subordinate subgreywacke  | Quartzite  |
| Quartzite, siltstone, conglomerate, shale  | Quartzite  |
| Quartzite, siltstone, conglomerate, shale, andesite  | Quartzite  |
| Quartzitic sandstone, mudrock and (in the west) conglomerate  | Quartzite  |
| Shale, minor limestone/dolomite, basalt and tuff  | Shale  |
| Shale, quartzite, conglomerate, breccia, diamictite  | Shale  |
| Shale, subordinate siltstone, minor quartzite  | Shale  |
| Shale/hornfels and minor carbonate rocks overlain in the south by argillaceous quartzite and arkose | Shale  |
| Tuff and agglomerate overlain by pillow basalt  | Tuff and agglomerate  |

![pta_group_rain](https://user-images.githubusercontent.com/22145011/153000477-c0c8ada2-3f63-453e-83b0-d47dcaddb7a3.png)
Figure 2. The mean annual precipitation (MAP) of the Pretoria Group. The gray background indicates the grassland biome.

Data sources:
- South African National Vegetation Map 2018 (SANBI) (https://bgis.sanbi.org/SpatialDataset/Detail/1674)
- Worldclim BIO Variables (https://doi:10.1002/joc.1276)
- Surface lithology from SA Council for Geoscience (sourced by Elaine)
