# Navin's Assignment 2: Cleaning and analyzing data


## DC Crime Data

- The interesting question you answered and why it could meet standards of newsworthiness for AU's audience.
- The steps you took to answer it, including how you built your pivot table.
- The answer to the question.

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

+ link to Emma's

- In addition to searching for other stories that have been done on this topic, please identify at least three high-quality datasets you could use in your story.
-   For each, please write why the data source is trustworthy and what (if any) limitations it might have.
-   Be prepared to discuss with me and the class what you find.

### Guide
- You only need to turn in one assignment for your group, but it would be helpful for me if everyone had a link to it in their Github repo for grading purposes. So it should work something like this:
-   One person in group uploads the written markdown file to Github
-   That person shares the URL of the file with other students
-   Other students in group link to that file as part of their assignment3.md


## AI Disclosure

### No AI was used in the research, cleaning, analyzing, or any other part of my process for this assignment.

