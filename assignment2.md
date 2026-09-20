
# Navin's Assignment 2: Build onto an existing database


Database Used:
[Runners Dataset](https://www.kaggle.com/datasets/beridzeg45/runners-dataset?resource=download)

This database is a collection of the fastest times for men and women in the following track & field events: 100m, 200m, 400m, 800m, 1500m, 3000m and 10,000m. The database was created by a user with the name *beridzeg45* on a site similar to Github called Kaggle where users can share and find datasets of different things. This specific dataset was last updated about 1 year ago meaning the data is almost fully up-to-date, but not quite. The dataset was sourced from the list by [All Time Athletics](https://www.alltime-athletics.com/).

### Reporting Question(s)
How do the wind readings of all of these times change how valid/not valid they are as records? What extra context do the wind readings give for the track & field community?

An important piece of data that is missing from these times is the wind reading. In the world of track & field, the standardized rules set by World Athletics state that times measured with a wind reading of positive (+) 2.0 [m/s] or greater cannot count as a legally recorded time. I doubt that the top records on this list are illegally measured times, but I think that having the wind results is a necessary component in this dataset. Other than that, location and/or altitude would be useful categories to have, because high altitude locations usually result in faster sprint times overall due to the low pressure and lower air resistance.

[Expanded Dataset]()

### Judgement Calls/Unusual Record
When looking through the data, I initially wanted to do the top 10 records for the 100m dash for both women and men, but unfortunately, it looks like the data was messed up. The entire women's 100m data entry list is full of just Florence Griffith Joyner's name and increasing numbers. In short, it didn't have data on the women's 100m dash so I decided to just do mens. I chose to do the top 11 times instead of the top 10 because the 10th and 11th fastest times were identical.

### Notes
In my data sheet, I noted a few things about the top 11 times. To briefly summarize, the top 11 fastest 100 meter dashes ran, of all time are actually only ran by 5 distinct people (Usain Bolt 4x, Tyson Gay 2x, Yohan Blake 1x, Asafa Powell 2x, Justin Gatlin 1x). Only 2 of the 11 times ran were ran in conditions with wind speeds less than or equal to 0.0 [m/s]. The fastest 100m dash of all time that wasn't aided by wind at all is the 3rd fastest time by technicality of the rules of World Athletics (Usain Bolt, 9.69s). The fourth fastest 100m dash rides the line between illegal and legal with a wind reading of (+) 2.0 [m/s]. The fifth fastest 100m dash of all time was ran with a headwind of (-) 0.1 [m/s], making it seemingly more impressive than times ran with positive backwinds.

No AI was used for the finding, researching, and organizing of this data. Below are the sources I used:

[Runners Dataset](https://www.kaggle.com/datasets/beridzeg45/runners-dataset/data)

[World Athletics](https://worldathletics.org/records/all-time-toplists/sprints/100-metres/all/men/senior?regionType=world&timing=electronic&windReading=regular&page=1&bestResultsOnly=false&firstDay=1899-12-31&lastDay=2026-09-19&maxResultsByCountry=all&eventId=10229630&ageCategory=senior)




