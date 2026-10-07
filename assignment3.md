# Navin's Assignment 3: Cleaning and analyzing data*
*Note: I submitted this assignment at 7:15 PM, 1 hr + 45 minutes after the posted deadline so it is *late*

## DC Crime Data

Editing Link: [data on crime reports within one mile of AU's campus]([https://american0-my.sharepoint.com/:x:/g/personal/ng3757a_american_edu/IQD5rqRyd3iZR7EnnWz5bGbYAbtGXyeREbdUPkymqEFoYa0?e=fs8Vv7](https://american0-my.sharepoint.com/:x:/g/personal/ng3757a_american_edu/IQD5rqRyd3iZR7EnnWz5bGbYAbtGXyeREbdUPkymqEFoYa0?e=6jpmX4))

My question: In the mile radius of AU, what is the majority of the crimes that occur and what neighborhood cluster does it show up in most commonly?

This question is newsworthy for an AU audience because it can inform people, who go to or work at AU, of neighborhood clusters that may be classified as more dangerous. It can also give an AU audience an opening to explore further, why these crimes happen and how they might be able to change that fact. Finally, it can be useful to journalism majors at AU who want to gather more experience for their area of study.

First, I highlighted all the data and created a Pivot Table that included *OFFENSE* and *NEIGHBORHOOD CLUSTER*. I placed *OFFENSE* in the Sum of Values tab in order to count up the number of offenses. I placed *NEIGHBORHOOD CLUSTER* in the Rows tab in order to organize the summed up *OFFENSE* data. What I found was an overwhelming majority of "theft/other". I took the number of "theft/other" reports and divided it by the total number of offenses, then multiplied by 100. After this, I changed the parameters by placing *NEIGHBORHOOD CLUSTER* in the Rows tab and *OFFENSE* in both the Sum of Values tab and Column tab.

To find the majority of the crimes, I divided the number of "theft/other" crimes, 1271, by the total number of crimes, 2156, making it 58.95% of the crimes. This was an overwhelming majority compared to the rest of the listed crimes. For the neighborhood clusters, there were two which held the most common instances of "theft/other". Out of clusters 11, 13, 14, and 15, Cluster 14 held 511 of 1271 and Cluster 11 held 676 of 1271. To answer which held the most common "theft/other" crimes, I would say Cluster 11 with 676 of 1271. Cluster 11 held 53.19% of the crimes while Cluster 14 held 40.20% of them. This lets me conclude that Cluster 11 holds the most common number of "theft/other," which represents the majority of the crimes committed within a 1-mile radius of AU.


## Final Project Dataset

### Chosen Dataset
[UNICEF Source Link](https://data.unicef.org/resources/dataset/education-data/)

[UNICEF Original Dataset Excel Link](https://american0-my.sharepoint.com/:x:/g/personal/ng3757a_american_edu/IQDT5cAUfkBCQJ0UpacaiDngARLhL54pA4hBXMoTogi8FAY?e=cmOGTs)

[UNICEF Edited Dataset Excel Link](https://american0-my.sharepoint.com/:x:/g/personal/ng3757a_american_edu/IQA4oVt_YkGBSoAkAWza7prPAde_K9Fckue_q2i03EG7E1A?e=TnK4Ld)

What I did to clean this data was, first, change the heading formatting. As we talked about in class, many datasets like to get fancy with their headings and this was no different. The headings for this dataset were originally merged between Rows 1 and 2, so I altered this to make sure all headings were Row 1, and all data started on Row 2.

The interesting questions I answered were: How does the male measured literacy rate compare to the female measured literacy rate? Between the two, which made up the majority of the literacy rates on average?

To answer this, I needed to move both the *Female* and *Male* columns to a separate Pivot Table for analysis, along with the *Countries and areas* column. After moving the three terms to a Pivot Table, I placed *Countries and areas* into the Rows section. Then, I filtered out the *Countries and areas* that had no data by moving the *Female* and *Male* data columns into the Filters tab, then filtering out "blanks". After this, I selected only the *Female* column and placed it into the Sum of Values tab. I then took the average of the data using a formula and ended up with 81.43%. This number represent the average percentage of the female population literacy rate amongst all countries with data. I repeated the same process with the *Male* column and ended up with 87.13%. To find what makes up the majority of the two, you can simply compare percentages, but another way to gather more data is adding the two percentages up, then taking the difference of the 200 by the sum and you get the average rate of illiteracy amongst all recorded countries.

The answer to my question is that the average Male Literacy Rate amongst all countries with recorded data as of 2021 by UNICEF is 87.13% of those countries' populations, which ends up being greater than the average Female Literacy Rate which stands at 81.43% of the populations. This means that the Male Literacy Rate is higher, on average, within this dataset, and, that the average illiteracy rate within these parameters is about 31.44% of the populations.

## Story Research

[Emma's GitHub assignment3.md](https://github.com/EmmaWhis/datajournalism-fall2026/blob/bbf3080b1c64554c9ae14959c85dbb52e808d38f/Assignment3.md)

### Guide

-   EMMA uploads the written markdown file to Github
-   EMMA shares the URL of the file JYE & I
-   JYE & I link to that file as part of our assignment3.md

## AI Disclosure

### No AI was used in the research, cleaning, analyzing, or any other part of my process for this assignment.

