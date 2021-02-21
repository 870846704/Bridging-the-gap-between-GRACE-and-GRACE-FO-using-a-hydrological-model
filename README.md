# Bridging-the-gap-between-GRACE-and-GRACE-FO-using-hydrological-models

This data reconstructed the gap between GRACE and GRACE-FO using hydrological models. The Release 06 Version 02 GRACE and GRACE-FO dataset (RL06_v02) by the Jet Propulsion Laboratory (JPL) using 3 equal-area mass concentration blocks (mascons) solution was collected as observed data. Specific information can be found in the article of "Bridging the gap between GRACE and GRACE-FO using hydrological models". The information about GRACE dataset and mascon resolution can be found at https://grace.jpl.nasa.gov/.


Here is the introduction to the header of reconstruction:

"mascon.id": id of mascon in the mascon file at https://grace.jpl.nasa.gov/ 
"lon": longitude of the mascon center
"lat": Latitude of the mascon center
"year": Year of reconstruction time
"month" Month of reconstruction time
"model_no_B": Model_no before linear correction
"model_snow_B": Model_snow before linear correction
"model_no_A": Model_no after linear correction
"model_snow_A": Model_snow after linear correction
"model_best": Reconstruction from the best model with largest NSE in the validation period for an artificial gap
