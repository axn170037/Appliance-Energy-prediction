# ML-Project_-Data 
# Aim
Experimental data used to create regression models of appliances energy use in a low energy building.

    
#  Regression

# About the Data

Date: time (yr:mon:day:hr:min:sec)    |  Appliances: energy use in Wh   |  lights: Energy use of light fixtures in the house(Wh)  
T1: Temperature in kitchen area(C)            |                              RH_1: Humidity in kitchen area(%)      
T2: Temperature in living room area(C)        |                              RH_2: Humidity in living room(%)         
T3: Temperature in laundry room               |                              RH_3: Humidity in laundry room area(%)             
T4: Temperature in office room(C)             |                              RH_4: Humidity in office room(%)       
T5: Temperature in bathroom in (C)            |                              RH_5: Humidity in bathroom(%)                    
T6: Temperature outside the building (north side) in (C)     |              RH_6: Humidity outside the building (northside)%    
T7: Temperature in ironing room in (C)                       |               RH_7: Humidity in ironing room in (%)    
T8:Temperature in teenager room 2 in (C)                     |               RH_8: Humidity in teenager room 2 in (%) 

T9: Temperature in parents room in (C)                       |              RH_9: Humidity in parents room in %

To: Temperature outside (from Chievres weather station) in (C)   |           Pressure (from Chievres weather station): in mm Hg
RH_out: Humidity outside (from Chievres weather station) in (%)  |           Wind speed (from Chievres weather station): in(m/s)
Visibility (from Chievres weather station): Ordinal data         |           Tdewpoint (from Chievres weather station): Cat data
rv1: Random variable 1(nondimensional)                           |           rav2: Random variable 2(nondimensional)

Where indicated, hourly data (then interpolated) from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis, rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.
