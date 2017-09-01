# Forecasting road accidents
# Analysis of the influence of exogenous factors on the accident rate.
Work was done with use of public data: https://data.gov.uk/dataset/road-accidents-safety-data for 2005-2015.
Area: Great Britain (England, Scotland, Wales)
The main aim of reasearch – to identify the factors which affect the accident rate. The goal indicator – the number of accidents (per year, month, day, hour)
In addition to standard, well-known data, such as seasonality, day of the week, hour of the day, holidays, etc., were used also various exogenous data.
As a result of research, it was found out that various exogenous factors and their combinations have a real impact on the numbers of road accidents.
We created forecasting model on the base of neural network, which takes in consideration both standard and additional factors.
We will publish data of our forecast for 2016 in free access for evaluation of our model, but keep in mind that statistic of 2016 was not yet officially published. After publication of official data we will be able to compare data and make the conclusions regarding the degree of results validity. During work with data for 2005-2015 were found the problems which affect the learning accuracy of the model. The main one is incomplete data about road accidents. In «STATS19 Road accident with injury (police)» are entered only those road accidents, where people were injured or died. At the same time many accidents, where no one was injured, are not included in statistic. This is standard situation in many countries. Meanwhile, some companies, such as Insurance, Transport, etc., have more detailed data, but don’t publish them.
We hope that our model will make forecast with allowance for additional factors, and will help to fill some gaps in the official statistics. Why was taken exactly this goal indicator as numbers of road accidents?

In our opinion such indicators as “numbers of Injured and Died” don’t always give us the total picture.

For example:

At 10:00 am there were 12 road accidents, where no one was injured

At 14:00 pm there was 1 road accident with bus, where 5 were injured

How do you think – which of these hours were the most emergency?

Our forecast

Days of increased number of accidents for 2016 (compared to similar days - month, day of the week, etc. ):

2016-01-02,
2016-01-24,
2016-02-18,
2016-02-19,
2016-05-09,
2016-05-10,
2016-05-11,
2016-05-12,
2016-08-06,
2016-08-13,
2016-09-03,
2016-09-04,
2016-09-05,
2016-09-06,
2016-09-28,
2016-09-29,
2016-09-30,
2016-10-01,
2016-10-17,
2016-10-18,
2016-10-19,
2016-10-20,
2016-10-21,
2016-10-26,
2016-10-27,
2016-10-28,
2016-10-31,
2016-11-14,
2016-11-15,
2016-11-26,
2016-11-27,
2016-11-28,
2016-12-23,
2016-12-24,
2016-12-26
