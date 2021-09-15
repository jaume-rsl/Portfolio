# Table of contents
# Data visualizations and analysis examples
1. [World Happiness Report Data](#World-Happiness-Report-Data)
2. [Some random securized screenshots](#Some-random-securized-screenshots)
    1. [COVID impact in my reporting area](#COVID-impact-in-my-reporting-area)
    2. [Other interesting dashboards](#Other-interesting-dashboards)

# Data extraction and modelling


# Data visualizations and analysis examples
## World Happiness Report Data

> Data downloaded from [this Kaggle dataset](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021)

>NOTE: A new table has been created linking areas and regions. Is was added to the model to relate historical data with 2021 data as well as to fill the gaps in the original dataset.
>It's also added a table which includes historical data and 2021 data for analysis purposes.
>![Data Model](https://github.com/jaume-rsl/Portfolio/blob/44fcd45e2b22d2e78d0a5d8a126fe2da39ee98e8/Power%20BI/19%20-%20Happiness%20report%20-%20Model.JPG)

We have a healthy dataset here, even if I don't like voids...
![Data Health](https://github.com/jaume-rsl/Portfolio/blob/8b5ada711d3bb4633ce11f3a38e28575baa5d08d/Power%20BI/18%20-%20Dataset%20Health.jpg)

First, we want to have a look of what influences subjective happiness. Subjective happines will be measured with the Cantril Ladder, which is a score given by a person to his/her own life, based on which is the best possible life they imagine (that would score 10).

![Component factors of Life Ladder](https://github.com/jaume-rsl/Portfolio/blob/e1a3bee8e8d23776d25214339cc1d313d759e0ea/Power%20BI/10%20-%20Happiness%20report%20-%20Component%20factors%20of%20Life%20Ladder.JPG)

We can have a closer look at Cantril ladder. Fisrt, to see how the scores are distributed worldwide. Then, we can select regions and countries to see a regional distribution, the historical evolution and the latest score compared to the 2020 score as a KPI.

![Life Ladder](https://github.com/jaume-rsl/Portfolio/blob/44fcd45e2b22d2e78d0a5d8a126fe2da39ee98e8/Power%20BI/11%20-%20Happiness%20report%20-%20Cantril%20Ladder.JPG)

Let's look at some KPIs

![KPIs](https://github.com/jaume-rsl/Portfolio/blob/6db2b744645a68ee3ff0dd26e32bde66bf8fbc74/Power%20BI/12%20-%20Happiness%20report%20-%20KPIs.JPG)

## Some random securized screenshots
### COVID impact in my reporting area

In the first place the model, linking some tables stored in Sharepoint Server
![COVID Model](https://github.com/jaume-rsl/Portfolio/blob/84ed9b8a345c81babc9a3795a6f473313981805c/Power%20BI/08%20-%20COVID%20-%20Modelo%20-%20SEC.jpg)

And then the data visualization
![COVID Map](https://github.com/jaume-rsl/Portfolio/blob/84ed9b8a345c81babc9a3795a6f473313981805c/Power%20BI/07%20-%20COVID%20-%20Mapa%20-%20SEC.jpg)

### Other interesting dashboards
Near real-time monitoring of allocated credit and current expenses:
![Creditos](https://github.com/jaume-rsl/Portfolio/blob/84ed9b8a345c81babc9a3795a6f473313981805c/Power%20BI/06%20-%20CREDITOS%20-%20SEC.jpeg)

A time-series dataset extracted form SSAS (SQL Server Analytics Service) with custom KPI and basic forecasted trend:
![Trend](https://github.com/jaume-rsl/Portfolio/blob/84ed9b8a345c81babc9a3795a6f473313981805c/Power%20BI/09%20-%20Bulk%20data%20time%20series,%20KPI%20and%20trend.jpg)
