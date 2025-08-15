######################
Product
######################

The MLGFS model runs 4 times a day at 00Z, 06Z, 12Z, and 18Z cycles. The horizontal resolution is on 0.25 degree lat-lon grid.
The vertical resolutions are on both 13 and 37 pressure levels.

* The 13 pressure levels include:

  50, 100, 150, 200, 250, 300, 400, 500, 600, 700, 850, 925, and 1000 hPa. 
    
* The 37 pressure levels include: 

  1, 2, 3, 5, 7, 10, 20, 30, 50, 70, 100, 125, 150, 175, 200, 225, 250, 300, 350, 400, 450, 500, 550, 600, 650, 700, 750, 800, 825, 850, 875, 900, 925, 950, 975, and 1000 hPa. 

The model output fields are:

* 3D fields on pressure levels:

  * temperature
  
  * U and V component of wind

  * geopotential height

  * specific humidity

  * vertical velocity

* 2D surface fields:

  * 10-m U and V components of wind

  * 2-m temperature

  * mean sea-level pressure

  * 6-hourly total precipitation


The 10-day forecast results for the current cycle found in the following directories:

  mlgfs/v1.0/mlgfs.yyyymmdd/hh
