# READ ME

## analysis files:
* 0_data_prep: data cleaning 
* 1_agreement: summaries of rater demographics, measures of inter-rater agreement
* 2_results: summaries and plots of rating data, summaries of model self-report data

## data folder:
### raw & cleaned data files:
* manyfaces_ratings_exp.csv & manyfaces_ratings_exp_cleaned.csv (rating data)
* manyfaces_ratings_quest.csv & manyfaces_ratings_quest_cleaned.csv (rater self-report data)
* note that model self-report data can be accessed with the photo database & cannot be shared here

### data cleaning steps
* exclusions.csv (record of rating data exclusions)
* recodes.R (gender & ethnicity recoding script)
* eth_recode.csv (record of model self-reported ethnicity recoding)
* gender_recode.csv (record of model self-reported gender recoding)
* quest_eth_recode.csv (record of rater self-reported ethnicity recoding)

### other
* custom_functions.R (functions used in the analysis files)
* project_1136_structure.json (norming/validation study structure)
* resampling_hehmanetal.R (point of stability script from Hehman et al. 2025)

## results folder:
* manyfaces_ratings_emotions.csv (averaged emotion intensity ratings & emotion categorization proportions per target)
* manyfaces_ratings_traits.csv (averaged trait ratings per target)
