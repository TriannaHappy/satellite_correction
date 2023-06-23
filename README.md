# Satellite Correction
This is the repositories for correcting rainfall data from satellite (such as CHIRPS, GPM, and GsMap). 
The step for correcting the satellite data needs to be done after finishing the quality control of observation data that will be used as a reference for correcting satellite data.

## Objective to correct the data :
1. Collecting the rainfall station data outside the domain research
2. Collecting the rainfall satellite data outside and inside the domain research
3. Analyze the rainfall seasonal pattern spatially to get the closest character to the domain research
4. QC all the rainfall station data
5. Grouping all the rainfall data `(satellite and station)` into [BMKG categories](https://www.bmkg.go.id/cuaca/probabilistik-curah-hujan.bmkg).
   - 0 mm/hari (abu-abu) : Berawan
   - 0.5 – 20 mm/hari (hijau) : Hujan ringan
   - 20 – 50 mm/hari (kuning) : Hujan sedang
   - 50 – 100 mm/hari (oranye): Hujan lebat
   - 100 – 150 mm/hari (merah) : Hujan sangat lebat
   - lebih dari 150 mm / hari (ungu) : Hujan ekstrem
6. Correcting the satellite data using quantile mapping
7. Evaluate the correction factor
8. Decide the best factor correction for the domain research
