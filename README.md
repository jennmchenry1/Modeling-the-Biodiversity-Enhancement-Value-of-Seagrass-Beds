# Modeling-the-Biodiversity-Enhancement-Value-of-Seagrass-Beds

Code and model outputs supporting the publication McHenry, J. et al. 2021. Modeling the biodiversity enhancement value of seagrass beds. Diversity and Distributions.

# Folders
final_datasets ->
1. 'FWCC_FIM_seagarss_data.csv' ->  the final dataset used for modeling the distribution of seagrass species and the total percent cover of seagrass beds along the Florida Gulf Coast. This dataset contains seagrass species and total cover observation from seine and otter trawl surveys conducted monthly by the Florida Fish and Wildlife Conservation Commission Fisheries Independent Monitoring Program between 0 to 4 meters water depth and from 1997 to 2017, spatially thinned to be no closer than 90m apart within a given year /month combo. Seagrass observations are supplemented by seascape and environmental datasets from FWCC, BioOracle, usSEABED, and other publicly available sources.
2. 'FWCC_FIM_faunal_richness_seine_survey_data.csv' -> the final dataset used for modeling shallow water faunal richness along the Florida Gulf Coast. This dataset contains faunal species richness observations from seine surveys conducted monthly by the Florida Fish and Wildlife Conservation Commission Fisheries Independent Monitoring Program between 0 to 2 meters water depth and from 1997 to 2017, spatially thinned to be no closer than 90m apart within a given year /month combo. Shallow water faunal richness observations are supplemented by seascape and environmental datasets from FWCC, BioOracle, usSEABED, and other publicly available sources.
3. 'FWCC_FIM_faunal_richness_ottertrawl_survey_data.csv' - the final dataset used for modeling deep water faunal richness along the Florida Gulf Coast. This dataset contains faunal species richness observations from otter trawl surveys conducted monthly by the Florida Fish and Wildlife Conservation Commission Fisheries Independent Monitoring Program between 2 to 4 meters water depth and from 1997 to 2017, spatially thinned to be no closer than 90m apart within a given year /month combo. Deep water faunal richness observations are supplemented by seascape and environmental datasets from FWCC, BioOracle, usSEABED, and other publicly available sources.

final_models -> 
1. 'seagrass_cover_tweedie_GAMM.rds' -> the highest performing generalized additive mixed model of total seagrass cover, developed using the final seagrass dataset.
2.'turtlegrass_binomial_GAM.rds' -> the highest performing generalized additive model of turtle grass (Thalassia testudinum) distribution, developed using the final seagrass dataset.
3. 'manateegrass_binomial_GAM.rds' -> the highest performing generalized additive model of manatee grass (Syringodium filiforme) distribution, developed using the final seagrass dataset.
4.'shoalgrass_binomial_GAM.rds' -> the highest performing generalized additive model of shoal grass (Halodule wrightii) distribution, developed using the final seagrass dataset.
5. 'biodiversity_shallowater_nb_GAMM.rds' -> the highest performing generalized additive model of shallow water faunal biodiversity, developed using the final shallow water faunal richness dataset.
6. 'biodiversity_deepwater_nb_GAMM.rds' -> the highest performing generalized additive model of deep water faunal biodiversity, developed using the final shallow water faunal richness dataset.

model_output ->
1. 'seagrass_stack.rds' -> a raster stack of mapped predictions for the total cover of seagrasses and probability of occurrence for dominant seagrass species across the Florida Gulf Coast under current conditions (2017-2020) and at 2100 under two sea level rise scenarios (i.e., +0.5m and +1.0m). 
2. 'faunal_biodiversity_stack.rds' -> a raster stack of mapped predictions for the faunal biodiversity associated with seagrass beds (including potential restoration areas) in shallow and deep water of the Florida Gulf Coast under current conditions (2017-2020) and at 2100 under two sea level rise scenarios (i.e., +0.5m and +1.0m).
3. 'BEV_stack.rds'-> a raster stack of mapped predictions for the biodiversity enhancement value (BEV) of suitable seagrass beds (including potential restoration areas) in shallow and deep water of the Florida Gulf Coast under current conditions (2017-2020) and at 2100 under two sea level rise scenarios (i.e., +0.5m and +1.0m).
4. 'management_stack.rds' -> a raster stack of containing maps showing suitable areas for seagrass beds and potential restoration areas under current conditions (2017-2020) and at 2100 under two sea level rise scenarios (i.e., +0.5m and +1.0m)

scripts -> 
1. TBD
2. TBD
3. TBD

