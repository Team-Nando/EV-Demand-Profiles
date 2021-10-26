# EV Profiles
This repository hosts realistic electric vehicle (EV) demand profiles produced by The University of Melbourne using data from the Electric Nation trial in the UK. These EV profiles are very useful to carry out different EV studies and can be used by distribution companies, consultancies, researchers, students or any other interested party.

The EV profiles correspond to light-duty EVs and only consider home charging. The EV profiles are divided into 4 groups based on their charging level (level 1/level 2) and type of day (weekday/weekend). At this stage, only the diversified profiles are available. They have been produced for groups of 100 EVs (useful for studies involving a distribution transformer with up to 100 home chargers/EVs) and for 1,200 EVs (useful for studies involving primary substations with thousands of home chargers/EVs).

## Original Data Source: Electric Nation Trial 
All the EV profiles were created using real data from the UK trial called Electric Nation. Only EVs whose charging was not managed or controlled were considered to capture the normal behaviour of EV users. Two types of home EV chargers are considered:
*	Level 1, with a demand of 3.68kW (16A, 230V); and,
*	Level 2, with a demand of 7.36kW (32A, 230V).

Further information about the original data can be found using the links below:
* Original data from Electric Nation: https://www.westernpower.co.uk/electric-nation-data
* Summary of Electric Nation Project: https://www.eatechnology.com/wp-content/uploads/2020/06/Electric-Nation-Report.pdf
* Electric Nation Project website (now updated with a new V2G focus, not considered): https://electricnation.org.uk/

## Creation of Individual EV Profiles
Details about the creation of the 1-min resolution 24-hour individual EV profiles (not available in this repository) and the corresponding considerations as part of the EV Integration project can be found in the following report:
* Milestone 6 "Network Modelling and EV Impact Assessment": https://www.researchgate.net/publication/354907164_Milestone_6_Network_Modelling_and_EV_Impact_Assessment


More information about the EV Integration project can be found on the website below:
* EV Integration Project: https://electrical.eng.unimelb.edu.au/power-energy/projects/ev-integration

## Creation of Diversified EV Profiles
* [x] Studies involving a distribution transformer with 100 EVs. The median and the 75th percentile are extracted from 100 samples each representing the average demand of a group of 100 individual 1-min resolution 24-hour EV profiles. This is done for each of the four groupds (level 1/level 2 and weekday/weekend). The figures below show, for each of the four groups, the 100 samples in transparent colour (green for level 1 and blue for level 2), the median (in yellow), the 75th percentile (in light blue). For comparison purposes, the corresponding diversified profile for 1,200 EVs (in red) is also included.

* [x] Studies involving a primary substation with 1,000 EVs or more. The average is extracted from 1,200 individual 1-min resolution 24-hour EV profiles for each of the four groups. From the figures, it can be seen that the diversified profile of 1,200 EVs is similar to the medians of 100 EVs. But the 75th percentiles of 100 EVs can have a higher demand (on average per EV) due to lower diversity.

## List of Diversified EV Profiles and Figures
You will find the following 1-min resultion 24-hour diversified EV profiles in this repository.
* Weekday - Level 1 - Diversified (Median) of 100 EVs
* Weekday - Level 1 - Diversified (75th percentile) of 100 EVs
* Weekday - Level 1 - Diversified (Average) of 1,200 EVs
* Weekday - Level 2 - Diversified (Median) of 100 EVs
* Weekday - Level 2 - Diversified (75th percentile) of 100 EVs
* Weekday - Level 2 - Diversified (Average) of 1,200 EVs
* Weekend - Level 1 - Diversified (Median) of 100 EVs
* Weekend - Level 1 - Diversified (75th percentile) of 100 EVs
* Weekend - Level 1 - Diversified (Average) of 1,200 EVs
* Weekend - Level 2 - Diversified (Median) of 100 EVs
* Weekend - Level 2 - Diversified (75th percentile) of 100 EVs
* Weekend - Level 2 - Diversified (Average) of 1,200 EVs

Below are the corresponding figures.

|Weekday Level 1 Profiles |
|-------------------------------------|
|![weekday-level1](https://user-images.githubusercontent.com/65996811/138627152-5c7714dc-d63c-450c-8f1c-820c961ca90e.png)|

|Weekday Level 2 Profiles |
|-------------------------------------|
|![weekday-level2](https://user-images.githubusercontent.com/65996811/138627169-6ffdc765-0989-48a4-aee1-45e800c29966.png)|

|Weekend Level 1 Profiles |
|-------------------------------------|
|![weekend-level1](https://user-images.githubusercontent.com/65996811/138627213-8d707fa2-5139-4ca1-8785-f9c4c98cb30d.png)|

|Weekend Level 2 Profiles |
|-------------------------------------|
|![weekend-level2](https://user-images.githubusercontent.com/65996811/138627230-47289673-cc89-4eb5-bae3-1d680c12b024.png)|


## Credits
Jing Zhu (jing.maviszhu@student.unimelb.edu.au)

Will Nacmanson (william.nacmanson@unimelb.edu.au)

Nando Ochoa (luis.ochoa@unimelb.edu.au)
