# COAWST_VEG
This repository contains the COAWST version to compute the effects of vegetation (along with two test cases 1) Analytical inputs to plant properties 2) NETCDF based inputs to plant properties

Brief History of Vegetation Folder 
Written by Tarandeep S. Kalra
06/10/2015
Co-editors : Neil K. Ganju, Alexis Beudin 

-------------------------------------------------
 TURNING ON VEGETATION  
************************************************
**#define vegetation** 
   #ifdef vegetation
     #ifdef ana_vegetation 
     #ifdef veg_rhs 
     #ifdef veg_turb 
     #ifdef veg_flex
    #ifdef wave_thrust_marsh
    #endif 
************************************************
