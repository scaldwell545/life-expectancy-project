# How Long Do You Expect to Live?

With the vast variety of resources, utilities, and factors around the world associated with our health as a human race, we were intrigued as to what kind of factors held correlations to longer life expectancies around the globe.
To understand the difference in life expectancy throughout the world, we decided we would find its association to key factors such as the prevalence of physicians and pharmacists, basic handwashing, drinking water services, and basic sanitation services. Using data that spans several decades from the past century, we revealed some obvious and not so obvious correlations to the length of human life!

**Research Questions to Answer**
1. How does access to water effect life expectancy?
2. Do hand washing habits correlate with life expectancy?
3. How does access to basic sanitation services correlate with overall life expectancy?
4. Does the number of Pharmacist in a country’s population correlate with the overall life expectancy?
5. Does the number of Medical Doctors in a country’s population correlate with the overall life expectancy?
6. How do various infrastructural factors correlate with each other  (Medical Doctors per 10,000 vs Population using at least basic sanitization services (%),  etc.)

**Datasets Used**
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete
- https://www.kaggle.com/sansuthi/life-expectancy
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=basicDrinkingWaterServices.csv
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=basicHandWashing.csv
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=atLeastBasicSanitizationServices.csv
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=medicalDoctors.csv
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=pharmacists.csv

![Life Expectancy Heatmap](https://github.com/scaldwell545/life-expectancy-project/blob/main/graphs/averageLifeExpectancyPerCountry.png?raw=true)

**Results**
1. How does access to water effect life expectancy? Do hand washing habits correlate with life expectancy?

Access to clean water, obviously, correlates highly with life expectancy (r = 0.81). Similarly, household access to hand-washing facilities correlates strongly to life expectancy (r = 0.82). These results should be obvious as cleanliness and clean, drinkable water are vital in living a long and healthy life. 

2. How does access to basic sanitation services correlate with overall life expectancy?

Again, similar to our previous two questions, life expectancy and access to basic sanitation services have a high correlation with each other (r = 0.84). This was to be expected as access to these services indicates that there is at least some more developed public infrastructure and therefore a better quality of life (in theory).

3. Does the number of Pharmacist in a country’s population correlate with the overall life expectancy? Does the number of Medical Doctors in a country’s population correlate with the overall life expectancy?

Our results here were a little more surprising. Compared to our levels of correlation between infrastructure related variables and life expectancy, the number of medical doctors and pharmacists in the population have a lower correlation to life expectancy (r=0.62 and r=0.63, respectively). Though these r-values aren’t necessarily weak, they suggest that these variables have a lesser impact on a country’s life expectancy than those discussed earlier. This might be initially counter-intuitive as we associate these medical professionals with a higher quality of life and therefore a higher life expectancy. Why might this be the case?

4. How do various infrastructural factors correlate with each other?

Although the presence of doctors or pharmacists in a population doesn’t correlate highly with life expectancy, there does exist a correlation between infrastructure related variables and the presence of these individuals in a country’s population (r = 0.68 for medical doctors per 10,000 vs the percentage of a population using at least basic sanitation services for example). 

This might suggest that when a country has more money to invest in public infrastructure, like water and sanitation services, more specialized healthcare workers arise in the population as the country is able to support them. This could be, in part, due to increased investment in education in more developed countries which would therein increase opportunities for those who pursue education in healthcare. More research would have to be done to support this connection, however.

