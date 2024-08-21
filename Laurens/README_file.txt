Both "Visit_data.rds" and "Observation_data.rds" are in RDS-format and should be used in the program R.


Visit data:
- Site: 	site ID of visit, 1 x 1 km grid cells
- Visit:	visit ID
- Year:		year of visit, period: 2012 - 2019
- Date:		date of visit, period: 2012 - 2019
- Observer:	observer ID, the observer that uploaded observations to the database
- N_observers:	number of observers for a single list of observations
- Duration:	number of hours spent observing
- N_species:	raw number of unique species recorded during the visit

Observation data
- Site: 	site ID of visit, 1 x 1 km grid cells
- Visit:	visit ID
- Year:		year of visit, period: 2012 - 2019
- Date:		date of visit, period: 2012 - 2019
- Species:	species ID, as used by FLORON in their database