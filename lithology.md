# Site selection based on surface lithology
Interactive viewer, clipped to only show quartzite/andesite dominated soils within the Pretoria Group: https://jdmwhite.users.earthengine.app/view/site-selection-quartz

Extracted environmental variables for sites suggested by Elaine:

|Name                           |      Lon|       Lat|MAP class     |PTA group              |Landforms          |Aspect | Sand %|
|:------------------------------|--------:|---------:|:-------------|:----------------------|:------------------|:------|------:|
|Amersfoort/ Maquabe            | 30.20994| -26.96541|NA            |NA                     |NA                 |NA     |     NA|
|Boskopdam NR                   | 27.11452| -26.52887|NA            |NA                     |NA                 |NA     |     NA|
|Lekwena 1                      | 27.19148| -26.62337|dry (< 650mm) |Andesite, conglomerate |Lower slope (flat) |E      |     63|
|Lekwena 2                      | 27.16647| -26.63624|dry (< 650mm) |Andesite, conglomerate |Lower slope (warm) |SW     |     63|
|Nooitgedacht NR                | 30.62289| -25.97972|NA            |NA                     |NA                 |NA     |     NA|
|Paulpietersburg                | 30.90297| -27.53917|NA            |NA                     |NA                 |NA     |     NA|
|Roodekraal South               | 27.14690| -26.84755|dry (< 650mm) |Andesite, conglomerate |Lower slope (flat) |NW     |     58|
|Roodekraal 1                   | 27.13234| -26.83140|NA            |NA                     |NA                 |NA     |     NA|
|Roodekraal 2                   | 27.13222| -26.82677|NA            |NA                     |NA                 |NA     |     NA|
|Rooipoort 1                    | 27.17704| -26.83098|dry (< 650mm) |Andesite, conglomerate |Lower slope (flat) |W      |     55|
|Rooipoort 2                    | 27.18111| -26.81696|dry (< 650mm) |Andesite, conglomerate |Lower slope (flat) |S      |     52|
|Taaibosbult 1                  | 27.93741| -26.87191|NA            |NA                     |NA                 |NA     |     NA|
|Taaibosbult 2                  | 27.93101| -26.85017|NA            |NA                     |NA                 |NA     |     NA|
|Verloren Vallei Nature Reserve | 30.11850| -25.30093|wet (> 650mm) |Quartzite              |Upper slope (warm) |S      |     44|
|Manzini Guest Farm             | 27.26087| -26.66356|dry (< 650mm) |Andesite, conglomerate |Upper slope (flat) |N      |     63|
|Limerick Lodge                 | 27.57741| -26.94163|NA            |NA                     |NA                 |NA     |     NA|
|Kamaoto Safaris                | 27.26192| -26.66293|dry (< 650mm) |Andesite, conglomerate |Upper slope (flat) |N      |     63|
|NW possible site #3            | 27.01778| -26.96882|dry (< 650mm) |Quartzite              |Lower slope (flat) |E      |     64|
|NW possible site #4            | 27.07036| -26.99207|dry (< 650mm) |Andesite, conglomerate |Upper slope (flat) |S      |     66|




Aspect is a derived product from the Shuttle Radar Topography Mission (SRTM) digital elevation model. The categories used to convert degrees to cardinal directions are:

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
| Hornfels, quartzite, carbonate and chert  | Hornfels, quartzite |
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
- Land form categories (https://developers.google.com/earth-engine/datasets/catalog/CSP_ERGo_1_0_Global_ALOS_landforms#description)
- Aspect derived from SRTM mission (https://developers.google.com/earth-engine/datasets/catalog/USGS_SRTMGL1_003?hl=en)
