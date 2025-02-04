![img](./images/notebook_header.png)
# Aircraft Analysis: Low-risk Aviation Investments

## Overview

This project focuses on finding low-risk Aviation aircraft. Investment companies can use this information to determine which aircraft makes and models would be the safest (ie, most profitable) to invest in.

The main approach here will be removing the human variables that may impact our dataset, in order to examine the data from a more "exact" perspective.

## Business Problem

Descriptive analysis of this dataset shows that certain makes, models, and types of aircraft appear to be significantly less likely to be involved in an accident than others. Choosing aircraft with one or two engines or those from overall safer companies such as Cessna, Piper, and Beech will allow investors to face significantly reduced risk.

## Data

We will be using the publicly available [Aviation Accident Data](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the United States [National Transport Safety Board](https://www.ntsb.gov/Pages/monthly.aspx). It contains very detailed information about each occurence, including flight information, weather, purpose of flight, and time of day. 

## Analysis [^1]
![img](./images/accidents_by_year.png)
We will be focusing on eliminating the 'human element' and less unpredicatable information from the dataset wherever possible. This approach will enable investors to make informed decisions about what they are investing in. Additionally, the weather conditions of flights will be evaluated. Although we cannot know how the weather will change day to day, it is a necessary relevant factor in determining an aircraft's reliability and should be accounted for.

## Results

![img](./images/engines.png)
- Single Engine Planes have the lowest injury rate per accident, based on our dataset.

![img](./images/top_30_makes.png)
- Cessna has the most injuries, but by far the most occurrences, making it a much lower risk investment than it appears to be.

![img](./images/weather.png)
- Adverse Weather and poor visibility conditions increase the likelihood of accidents and fatalities.

## Conclusions
- In terms of overall safety ratings for investing, we should stick to single engine planes for the majority of investments.
- Cessna is a great company to go with for single-company investing
- Weather has a significant effect on accident rates and cannot be ignored


[Business Presentation](presentation.pdf)


[Interactive Tableau Dashboard](https://public.tableau.com/app/profile/connor.anastasio/viz/AircraftInvestmentAnalysis/Dashboard1?publish=yes)

[^1]:For a full detailed analysis, please reference the [Jupyter Notebook](https://github.com/connoranastasio/dsc-phase-1-project-v3/blob/master/student.pdf) in this repository.