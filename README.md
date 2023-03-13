# HARMONIA_AQ
HARMONIA air quality analysis

## Introduction
This repository contains data from two CAMS data sets
 - CAMS Global reanalysis (EA4C)
 - CAMS European air quality Reanalysis 

Data have been extracted for areas surrounding the four HARMONIA target cities: Milan, Piraeus, Ixelles and Sofia

All the data have been pre-processed to mass concentrations in $\mu \text{g}\, \text{m}^{-3}$

Two jupyter notebooks demonstrate opening and plotting the data

 
###  CAMS Global reanalysis (EA4C)
See CAMS_Global_reanalysis_data_demo.ipynb

Currently available from 2003 to June 2022 (CAMS continue add more recent data)

0.75 degrees Horizontal resolution

3 hourly temopral resolution
 
### CAMS European air quality Reanalysis 
See CAMS_European_AQ_reanalysis_demo.ipynb

Available for 2018 to 2021 \
(CAMS intend to add more recent years, also plan to create historical data for O3, NO2 and PM10 for 2013 to 2017)

0.1 degrees Horizontal resolution

1 hourly temopral resolution

 
## Parameters of particular interest

Some key air quality parameters that are subject to targets/directives/standards/guidlines:
 - pm2p5 : Particulate matter d <= 2.5 um
 - pm10  : Particulate matter d <= 10 um
 - co    : Carbon monoxide mass concentration
 - no2   : Nitrogen dioxide mass concentration
 - no    : Nitrogen monoxide mass concentration
 - go3   : Ozone mass concentration
