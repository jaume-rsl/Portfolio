# Power BI jobs

## World Happiness Report Data

> Data downloaded from [this Kaggle dataset](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021)

>NOTE: Two new table has been created linking areas and regions. One is was added to the model to relate historical data with 2021 data as well as to fill the gaps in the original dataset.
>The other one, merges the historical data and 2021 data to netter represent some insights

>'''
>Indexes 2021 = SELECTCOLUMNS('world-happiness-report-2021',
                "Country Name", 'world-happiness-report-2021'[Country name],
                "Freedom to make life choices", 'world-happiness-report-2021'[Freedom to make life choices],
                "Generosity", 'world-happiness-report-2021'[Generosity],
                "Healthy life expectancy at birth", 'world-happiness-report-2021'[Healthy life expectancy],
                "Life Ladder", 'world-happiness-report-2021'[Ladder score],
                "Log GDP per capita", 'world-happiness-report-2021'[Logged GDP per capita],
                "Perception of corruption", 'world-happiness-report-2021'[Perceptions of corruption],
                "Social support", 'world-happiness-report-2021'[Social support],
                "year", "2021"
                )
>'''

>![Data Model](https://github.com/jaume-rsl/Portfolio/blob/44fcd45e2b22d2e78d0a5d8a126fe2da39ee98e8/Power%20BI/19%20-%20Happiness%20report%20-%20Model.JPG)



First, we want to have a look of what influences subjective happiness. Subjective happines will be measured with the Cantril Ladder, which is a score given by a person to his/her own life, based on which is the best possible life they imagine (that would score 10).

![Component factors of Life Ladder](https://github.com/jaume-rsl/Portfolio/blob/e1a3bee8e8d23776d25214339cc1d313d759e0ea/Power%20BI/10%20-%20Happiness%20report%20-%20Component%20factors%20of%20Life%20Ladder.JPG)

We can have a closer look at Cantril ladder. Fisrt, to see how the scores are distributed worldwide. Then, we can select regions and countries to see a regional distribution, the historical evolution and the latest score compared to the 2020 score as a KPI.

![Life Ladder](https://github.com/jaume-rsl/Portfolio/blob/44fcd45e2b22d2e78d0a5d8a126fe2da39ee98e8/Power%20BI/11%20-%20Happiness%20report%20-%20Cantril%20Ladder.JPG)

Let's look at some KPIs

![KPIs](https://github.com/jaume-rsl/Portfolio/blob/6db2b744645a68ee3ff0dd26e32bde66bf8fbc74/Power%20BI/12%20-%20Happiness%20report%20-%20KPIs.JPG)
