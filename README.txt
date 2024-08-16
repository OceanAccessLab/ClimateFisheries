Description of the file ecosytem_data.csv

It contains the information used to generate Figures S1 to S5.
Each

It contains the following columns:

1. "Year" (index)
Years from 1976 to 2022 


2. "primary_prod_mgC_m-3_d-1"
Annual net primary production (in mgC m−3 d−1) over the NW Atlantic was obtained from a Mercator-Ocean biogeochemistry hindcast for the global ocean at https://doi.org/10.48670/moi-00019 [consulted 4 October 2022].
The monthly resolution data were averaged in annual means and over a geographical region covering the NW Atlantic [47-65°N; 47-65°W] (dashed box in Figure 3).
The resulting time series runs from 1993 to 2020 (Figure S1).

3. "calfin_density_log10_ind_m-2"
Mean annual density of Calanus finmarchicus on the Newfoundland and Labrador shelf (in log10 of individuals per square meters).
This information is derived from the Atlantic Zone Monitoring Program
The resulting time series runs from 1999 to 2021 (Figure S2).

4. "capelin_biomass_index_kt"

Anual capelin biomass index (in kt) derived from the  annual Fisheries and Oceans Canada (DFO) spring acoustic surveys..
The spring capelin acoustic survey has taken place annually in its current form since 1982.
The resulting time series runs from 1982 to 2022 (Figure S3).

5. "multispecies_biomass_density_kt_km-2"
The total biomass density index from Fisheries and Oceans Canada (DFO) multi-species bottom-trawl scientific surveys (in kt km−2).
It was calculated from DFO Fall and Spring surveys for NAFO Divisions 2J3KLNOPs.
The resulting time series runs from 1982 to 2021 (Figure S4).

5. "delta_groundfish_biomass_kt"
Groundfish biomass was estimated using a state-space multi-species surplus production model for the Newfoundland and Labrador shelves.
Catch data were extracted from the STATLANT 21A database (https://www.nafo.int/Data/STATLANT-21A, accessed 2022-01-21) and stratified estimates of survey biomass were obtained from the Fisheries and Oceans Canada (DFO) multi-species bottom-trawl surveys within NAFO divisions 2J3K and 3LNO for the following species: Atlantic Cod, Haddock, White Hake, American Plaice, Redfish spp., Skate spp., Witch Flounder, Yellowtail flounder, Greenland halibut and Wolffish spp.
Within each region (2J3K and 3LNO), the biomass of each species at the start of year was estimated using the model described in the manuscript.
The process errors from this model correspond to variance unexplained by density-dependent processes and fishing mortality (i.e., changes presumably caused by environmental
variables) and presented here.
The resulting time series runs from 1976 to 2021 (Figure S5).


Description of the file NLCI_cumsum.csv

It contains the cummulative sum of the Newfoundland and Labrador Climate Index (NLCI) used to generate the magenta curve in Figure 2 and Figures S1 to S5.
The NLCI is available at: https://doi.org/10.20383/101.0301

It contains the following columns:

1. "Year" (index)
Years from 1950 to 2022 

2. Cumsum
Cumulative sum of the NLCI after a 2-year running mean has been applied.
