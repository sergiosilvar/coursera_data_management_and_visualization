


# Week 1 Assignment

I've chosen the Gapminder dataset because of its simplicity and I'm interested in studying countries social and economics differences. In a first atemp, I'm focusing in find which variables correlate the most between themselves. I'm hopping the correlation can be used to cluster countries by their economic development, cultural traits or politic system.So, in a first glance, I'm selecting the variables: Polity Score, Oil per person, Eletric consumption per person, Employment rate, Life expectancy, Armed force rate and Urban rate. 

As a second topic, I'm interest in evaluate how the variables above iteract with Female employment rate. The participation of womem in the labor market may be an effect of the democractic system, as the later tends to score the public opinion of overall citizens and women, I hope, must be an active part of society.

## Codebook selected

1. **Variable**: polityscore
 > **Description**: 2009 Democracy score (Polity). Overall polity score from the Polity IV dataset, calculated by subtracting an autocracy score from a democracy score. The summary measure of a country's democratic and free nature. -10 is the lowest value, 10 the highest.
  **Source**: Polity IV Project


2. **Variable**: oilperperson
    > **Description**: 2010 oil Consumption per capita (tonnes per year and person)
     **Source**: BP


3. **Variable**: relectricperperson
    >**Description**: 2008 residential electricity consumption, per person (kWh). The amount of residential electricity consumption per person during the given year, counted in kilowatt-hours (kWh).
    **Source**: International Energy Agency

1. **Variable**: employrate
    >**Description**: 2007 total employees age 15+ (% of population). Percentage of total population, age above 15, that has been employed during the given year.
    **Source**: International Labour Organization

1. **Variable**: lifeexpectancy
    >**Description**: 2011 life expectancy at birth (years)
The average number of years a newborn child would live if current mortality patterns were to stay the same.
    **Source**: 1. Human Mortality Database, 2. World Population Prospects, 3. Publications and files byhistory prof. James C Riley, 4. Human Lifetable Database.


1. **Variable**: armedforcesrate
    >**Description**: Armed forces personnel (% of total labor force)
    **Source**: Work Development Indicators

1. **Variable**: urbanrate
    >**Description**: 2008 urban population (% of total)
Urban population refers to people living in urban areas as defined by national statistical offices (calculated using World Bank population estimates and urban ratios from the United Nations World Urbanization
Prospects).
    **Source**: World Bank

1. **Variable**: femaleemployrate
    >**Description**: 2007 female employees age 15+ (% of population). Percentage of female population, age above 15, that has been employed during the given year.
    **Source**: International Labour Organization.

## Hypothesis proposed
1. The polity score variable can be measured as a regression of the others variables proposed. The score in the democracy model can be modeled by variables such as employment rate, consumption measure, productivity, military presence, economic development.
2. The share of female in the labor market and government is an indicator of politic freedom and thus, development.

## Bibliography 
1. [KNACK, Stephen; KEEFER, Philip. Institutions and economic performance: Cross-country tests using alternative institutional indicators. 1995.](http://www.oecd-ilibrary.org/science-and-technology/composite-indicators-of-country-performance_405566708255)
2. [MATLAND, Richard E. Women's representation in national legislatures: Developed and developing countries. Legislative Studies Quarterly, p. 109-125, 1998.](http://www.jstor.org/stable/440217)
3. [DASGUPTA, Partha; WEALE, Martin. On measuring the quality of life. World development, v. 20, n. 1, p. 119-131, 1992.](http://www.jstor.org/stable/2109407)
