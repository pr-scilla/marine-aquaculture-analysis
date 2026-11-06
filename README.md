# United States West Coast Aquaculture Analysis

### EDS 223 Homework Assignment 3

This assignment explores which Exclusive Economic Zones (EEZ) on the West Coast of the United States have suitable sea surface temperature (SST) and depth values for developing marine aquaculture for multiple species of oysters and Yesso scallop (*Mizuhopecten yessoensis*). The code outputs are two maps of west coast EEZ regions colored by amount of suitable area for oyster and Yesso scallop aquaculture.

Sea surface temperature data from [NOAA's Daily Global 5km Satellite Sea Surface Temperature Anomalyv3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php), bathymetry data from [General Bathymetric Chart of the Oceans](https://www.gebco.net/data-products/gridded-bathymetry-data#area), and Exclusive Economic Zone data from [Marineregions.org](https://www.marineregions.org/eez.php) were used to create the maps in this assignment.

## Repository Structure:

```{r}
MARINE-AQUACULTURE-ANALYSIS
│   README.md
│   oyster-and-yesso-scallop-aquaculture-analysis.pdf   # rendered .pdf of quarto document
│   oyster-and-yesso-scallop-aquaculture-analysis.qmd   # quarto document containing assignment code
└───.gitignore
     └───data                                           # folder containing data files for assignment
        └─── wc_regions_clean.shp                       # EEZ boundaries data
        └─── depth.tif                                  # bathymetry data
        └─── average_annual_sst_2008.tif                # sea surface temperature data
        └─── average_annual_sst_2009.tif
        └─── average_annual_sst_2010.tif
        └─── average_annual_sst_2011.tif
        └─── average_annual_sst_2012.tif
```

## Data Access

Data used in this assignment were sourced with permission through the [linked data folder](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?pli=1) on the [EDS 223 Homework Assignment 3 page](https://eds-223-geospatial.github.io/assignments/HW3.html).

## Contributors

Author: [Priscilla Pierce](https://github.com/pr-scilla)

## References

[EDS 223: Geospatial Analysis and Remote Sensing](https://eds-223-geospatial.github.io/) Instructor: Annie Adams