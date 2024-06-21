
## Data files and column descriptions:

CommonGarden_Data_With_ENV.csv --> CSV file containing quantitative trait measurements and envrionmental data from WorldClim2 dataset of 
1,438 *Q.rubra* acorns from 102 maternal lines from eight populations. These acorns were planted in a randomized block design with four blocks, with populations 
and maternal lines distributed as evenly as possible across the blocks, under a maximum temperature setting of 20°C, a minimum temperature setting of 11.6°C and
watered every 48hrs at the University of Minnesota Duluth greenhouse (46°49’00.7” N 92°05’12.1” W).

### Column description: 

1. ID: Individual number (1-1438)
2. Block: Block where individual was located
3. Population: Two letter code of collection site for each individual
4. Tree: Maternal tree ID
5. Acorn: Individual number for each acorn from each maternal tree
6. Coastal_NonCoastal: two factors (coastal/non coastal) of where collection site was located. Coastal sites are between 0-16 km from the shore of Lake Superior and non coastal sites are located between 17-160 km from the shore of Lake Superior.
7. Region: Sampling locations (referred to as “populations,” in the manuscript) that differed with respect to distance from Lake Superior: “Coastal” (0–16 km), “Inland” (17–80 km), and “Interior” (81–160 km)
8. Distance_from_LS_in_Km: Distance of colelction site from the nearest shore point of Lake superior in Km
9. Distance_from_LS_in_mi:  Distance of colelction site from the nearest shore point of Lake superior in miles
10. Latitude: Latitude of collection site
11. Longitude: Longitude of collection site
12. Acorn_Weight: Weight in grams of individual acorns before planting in the common garden
13. Rooted__Yes_No_: Binary variable (1/0) for wether an acorn had an emergent radicle before planting in the common garden
14. Germinated: Binary variable (1/0) for wether an acorn germinated after planting in the common garden
15. Julian_Date_Germition: Julian date (day of year in 2019) where germination was observed for the individual in the common garden
16. Log_Julian_Date_Germition_: log transformed Julian date (day of year in 2019) where germination was observed for the individual in the common garden
17. X06_17_19_Height: Plant stem height at week 4
18. Early_Growth_rate: Plant stem height growth rate calculated for the first four weeks of growth (W4-W1/4)
19. X08_19_19_Height: Plant stem height at week 11
20. Late_Growth_rate: Plant stem height growth rate calculated from week 5 - 11 growth (W11-W5/7)
21. Height_Growth_Rate: Plant stem height growth rate during the growing season (W11-W1/10)
22. X06_24_19_Diameter: Plant stem diameter at week 4
23. Early_Diameter_rate: Plant stem diameter growth rate calculated for the first four weeks of growth (W4-W1/4)
24. Late_diameter_rate: Plant stem diameter growth rate calculated from week 5 - 11 growth (W11-W5/7)
25. Diameter_Growth_Rate: Plant stem diameter growth rate during the growing season (W10-W1/10)
26. X06_17_19_Leaves: Plant leaf number at week 4
27. X06_24_19_Leaves: Plant leaf number at week 5
28. weight_g: Individual upper most expanded leaf weight collected at week 10
29. leaf_area_cm2: Individual upper most expanded leaf area collected at week 10
30. SLA_cm2_g_: Individual upper most expanded specific leaf area collected at week 10 (SLA = area/weight)
31. Log_SLA_cm2_g: log transformed individual upper most expanded specific leaf area collected at week 10 (SLA = area/weight)
32. Survived_Season__1_YES_: Binary variable (1/0) for wether an acorn survived the whole season after planting in the common garden
33. Mean_Annual_Temp: Mean annual temperature for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019:
34. Isothermality: Isothermality for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
35. Temperature_Seasolity: Temperature seasonality for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
36. Max_Temperature_of_Warmest_Month: Maximum temeprature of the warmest month for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
37. Min__Temperature_of_Coldest_Month: Minimum temperature of the coldest month for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
38. Annual_Precipitation: Annual precipitation for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
39. Precipitation_of_Wettest_Month: Precipitation of the wettest month for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
40. Precipitation_of_Driest_Month: Precipitation of the driest month for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
41. Precipitation_Seasolity__Coefficient_of_Variation_: Precipitation seasonality for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
42. Precipitation_of_Warmest_Quarter: Precipitation of the warmest quarter for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
43. Precipitation_of_Coldest_Quarter: Precipitation of the coldest quarter for each individual lat-long coordinates retrived from WorldClimDataset2 in 2019
44. Hardiness_Zone: USDA hardiness zone for each individual lat-long coordinates in 2019

    

