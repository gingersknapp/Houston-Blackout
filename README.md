# Houston Blackouts

This repository houses materials for HW2 for analyzing blackouts in Houston, Texas in 2021 following severe winter storms in mid February.  

This project estimates the number of homes that lost power in the Houston metropolitan area between February 7th and February 16th, 2021.  It compares night light intensity between the two nights and maps the general locations of homes estimated to have lost power.

## Repository Structure

|File/folder name             | Contents                            |
|:----------------------------|:------------------------------------|
|README.md                    | README for the repository           |
|houston-blackouts.qmd                | Analysis code document              |
|houston-blackouts.pdf                | Exportable analysis PDF             |
|.quarto/typst/packages/preview | Files for viewing houston-blackouts.pdf     |
|LICENSE                      | Use license                         |
|.gitignore                   | Untracked files                     |                            


## Data access

Data for this analysis is not contained in this repository.  However, VIIRS data used to assess lighting at night was obtained through NASA's [Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)](https://ladsweb.modaps.eosdis.nasa.gov/). for the nights of February 7, 2021 and February 16, 2021.

To control for lighting from roads, we obtained data of roads interesting the Houston area from [OpenStreetMap](https://planet.openstreetmap.org/) and  [Geofabrik](https://download.geofabrik.de/).  Data on houses in the area was also obtained through OpenStreetMap and Geofabrik.

## Authors
 - Olivia Knapp
 - [Annie Adams](https://github.com/annieradams) (Instructor)

## References
- Román, M.O., Wang, Z., Sun, Q., Kalb, V., Miller, S.D., Molthan, A., Schultz, L., Bell, J., Stokes, E.C., Pandey, B. and Seto, K.C., et al. (2018). NASA's Black Marble nighttime lights product suite. Remote Sensing of Environment 210, 113-143. [doi:10.1016/j.rse.2018.03.017]
(https://ladsweb.modaps.eosdis.nasa.gov/missions-and-measurements/products/VNP46A1). 

- OpenStreetMap contributors (2024). OpenStreetMap [Data set]. OpenStreetMap Foundation. Available as open data under the Open Data Commons Open Database License (ODbL) at openstreetmap.org. 