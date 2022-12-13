# Socio-economic-factors-and-Number-of-property-crimes
When I move to a new neighborhood, I'm mostly concerned about the risk of having to experience autothefts or break-ins and robberies. Leveraging on what I've learned in class, I want to create my own assessment model. We will look at various input variales, establish whether there is correlation between each of them and the number of crimes in each area, and arrive at a model that can predict the number of crimes based on identified predictors.

As violent crimes (rapes, murders, etc.) normally have other contributing factors beyond mere socio-economic attributes, we will not consider them under the scope of this project. Rather, we will focus on robberies, auto-thefts and burglaries which are primarily property offenses.

With regards to the possible predictors, we can use the list of crime factors from the website of North Carolina State Bureau of Investigation (* ) as a reference. Youth concentration, stability of population with respect to residents' mobility, educational characteristics, economic conditions and effective strength of law enforcement agencies were mentioned among those factors. From the data provided, some attributes could be considered as relevant indicators of such factors:

- percentage of those from 12-21 (youth concentration) for variations in composition of the population
number of homeless people for stability of population
- median income, percentage of unemployment, percentage of people under poverty level for economic conditions
percentage of people 25 and over with less than a 9th grade education for educational characteristic
- number of police officers for the relative presence of law enforcement unit
- population density and percent of persions living in dense housing conditions for population density and degree of urbanization
- percentage of population who are divorced for family conditions with respect to divorce and family cohesiveness

Using data from the 1990 census and the crime statistics from the 1995 FBI UCR, I aim to understand the correlation between those contributing factors with the crime rates and use the regression model to help determine a neighborhood’s crime rate, which in this case will be total number of burglaries, robberies, larcenies, and auto-thefts per 100k population.

(*) Source: North Carolina State Bureau of Investigation (2022). Crime Factors https://ncsbi.gov/Services/Crime-Statistics/Crime-Factors#:~:text=Economic%20conditions%2C%20including%20median%20income,Climate.
