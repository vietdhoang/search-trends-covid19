# Analysis of COVID-19 Search Trends and Hospitalizations

**COMP 551: Applied Machine Learning** <br />
**Authors: Viet Hoang, Eddie Cai, Wisang Sugiarta**

COVID-19 has changed the landscape of everyday life for humans all around the globe. Since the beginning of the pandemic, many researchers have devoted countless hours to predict where and how outbreaks can occur based on a variety of factors.  Corporations such as Google and Apple have helped this process by releasing important data sets about how populations have reacted to the pandemic. The data set of interest in this study is Google’s symptom search trends. With the advances of machine learning techniques and data visualization, this study’s objective is to create models that can predict hospitalization rates based on the symptom search trends in a region. The study will focus on three supervised machine learning techniques: k-Nearest Neighbours (k-NN), decision trees, and random forests.

## Datasets

Two datasets were used in this study. The first dataset are Google’s symptom search trends in a given week throughout all states in the US. This dataset provides a quantity that researchers at Google call the relative popularity of a symptomin a region. Essentially, it is the count of a given symptom search normalized by the probability of that symptom being searched on any given weekand by a normalized population in the region. This dataset gives contains the relative popularity of 420 different symptoms. This data was obtained on 19/10/2020.
- Dataset available [here](https://github.com/google-research/open-covid-19-data/blob/master/data/exports/search_trends_symptoms_dataset/README.md)

The second dataset is an open source dataset that aggregates daily public COVID-19 data, such asdeaths and hospitalizations amongst many more,into one set. This dataset not only includes the states in US but all the regions in the world, which we must filter out. This data was also obtained on 19/10/2020.
- Dataset available [here](https://raw.githubusercontent.com/google-research/open-covid-19-data/master/data/exports/cc_by/aggregated_cc_by.csv)
