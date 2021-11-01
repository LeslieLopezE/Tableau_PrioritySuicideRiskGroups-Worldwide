## Priority-Suicide-Risk-Groups-Worldwide (Tableau)

### Project objective

This project aims to provide direction to a not-for-profit mental health services organization to identify priority suicide-risk groups worldwide in order to determine the country and demographic their next project should focus on.

The main objective of this project is to visualize and find a relatable pattern in the data to get a better understanding of it and use the findings to answer find the most affected by suicide per country, age, gender & generation. The analysis will be focused on suicide rate (Suicide/100K population) for the years 1885 to 2016.

### Description of the dataset

The data set selected is the suicide data set, which has 27820 observations and 12 features, out of which five are numerical and the rest are categorical.

The target variable is the suicide number “suicide_no”. The independent or predictor variables are country, year, sex, age, population, country_year, HDIforyear, gdp_for_year, and generations. 
The data set also has 2 derived variables, suicide_100pop and gdp_per_Capita, which are calculated by dividing suicide_no and GDP_for_year by population.

The following is the description of each variable and its type in the data set, which shows gdp_for_year and HDIforyear as char type, the latter with length 1.

![image](https://user-images.githubusercontent.com/8260464/139686505-fcbe2434-3009-4d43-9b93-5d48ab2e7ff9.png)

We also can see a listing of the first 10 observations where we can see a significant number of missing values for HDIforyear and inconsistencies bet. age and generation.

![image](https://user-images.githubusercontent.com/8260464/139686551-46e378c5-706d-4743-8766-81ca111b0296.png)

### Findings and Conclusions

1. There is an association between GDP_per_Capita and Suicide_no or Suicide_100pop. The variables seem to follow a logarithmic distribution (non-linear)(Figure 1).
2. The annual GDP and suicide rates are associated inversely. This means that as annual GDP increases, suicide rates decrease and vice versa (Figure 2). Indeed, countries with high annual GDP recorded low suicide rates.
3. With Gdp_per_capita represented in blue bars and suicide rates as a red trend line, we see that in the year 1999, after 15 years of consecutive GDP growth, the suicide rates started declining ((Figure 3).
4. As a result og analyzing frequency distributions of suicide rates per gender and generation, this study found out that globally between 1985 and 2016, there was a clear disparity in suicide rate between genders, being the male suicide rate at least 4 times the female rate (Figure 4).
5. The generation with a higher suicide rate worldwide was the G.I. generation (the greatest generation), which is the generation that had more than 75 years in 1984 (FIGURE 4. This generation of people fought in World War II, which helps explain one of the reasons for suicide. Trauma caused by War is associated with PTSD, which could cause suicide according to the U.S. Department of Veteran Affairs and other mental health institutions.
