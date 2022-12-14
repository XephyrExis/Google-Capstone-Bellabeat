# Case Study: How Can a Wellness Technology Company Play It Smart

![https://free-vectors.net/_ph/4/2/589748984.jpg](https://free-vectors.net/_ph/4/2/589748984.jpg)
**Image:** Free-Vectors.net    **License:** [CC by 4.0](https://creativecommons.org/licenses/by/4.0/)

## Introduction

This is capstone project for Google Data Analytics Professional Certificate Case Study 2: How Can a Wellness Technology Company Play It Smart?


**Project Completed by:** Christopher Messer

**Project Date:** 9/6/2022

### Business Tasks

-	What are some trends in smart device usage?
-	How could these trends apply to Bellabeat customers?
-	How could these trends help influence Bellabeat marketing?

### Description of Data Sources
FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius on Kaggle). 
The content description on Kaggle states:

*“This dataset generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. Individual reports can be parsed by export session ID (column A) or timestamp (column B). Variation between output represents use of different types of Fitbit trackers and individual tracking behaviors / preferences.”*

  #### Data Limitations

  - The sample size of the provided dataset is small and does not reflect the overall userbase which increases the likelihood of bias within the data.  Increasing the sample size would mitigate this issue.

  - The data is missing information related to age, sex, type of activity performed, and device type which further limits analysis and marketing applications.

  - The data was produced in 2016, which means that the trends discovered and discussed here reflect that period of time.

### Stakeholders

- **Urška Sršen:** Bellabeat’s cofounder and Chief Creative Officer
- **Sando Mur:** Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

### Bellabeat Products

- **Bellabeat app:** The Bellabeat app provides users with health data related to their activity, sleep, stress,
menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and
make healthy decisions. The Bellabeat app connects to their line of smart wellness products.

- **Leaf:** Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects
to the Bellabeat app to track activity, sleep, and stress.

- **Time:** This wellness watch combines the timeless look of a classic timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your
daily wellness.

- **Spring:** This is a water bottle that tracks daily water intake using smart technology to ensure that you are
appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your
hydration levels.

- **Bellabeat membership:** Bellabeat also offers a subscription-based membership program for users.
Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and
beauty, and mindfulness based on their lifestyle and goals.

### Data Cleaning, Manipulation, and Assumptions
- Due to the smaller data volume, this is a project that can be completed within a spreadsheet. I've elected to use Microsoft Excel.
- Data for distance was not given a unit of measurement.  As Fitbit is an American company, I'll be acting on the assumption that distance is recorded in miles.
- Initial assessment of User IDs shows 33, despite the provided description of the dataset stating 30.  A count of User ID instances shows that 3 of the IDs had a fewer than 19 days of recorded activity compared to the average of 29.9 days for the other users during the 31 day range of the dataset.
- I've created a new xlsx file to host the data after to preserve the original dataset and titled it dailyActivityCleaned.
- Removed the 3 outliers (2347167796, 4057192912, and 8253242879) of the dataset to align with the provided description and improve quality of the assessment.
- Confirmed that the data types for each row aligned with the intent of the column.

### Holiday Trends
There were 3 holidays during the dataset's timeframe: Earth Day, Cinco de Mayo, and Mother's Day.
   - Earth Day saw a decrease of .15% in steps when compared to the average for Fridays, the day of the week on which it occurred, but saw an increase in Very Active minutes by 22.75% and an increase in Moderately Active minutes by 8.23%.
   - Cinco de Mayo saw an increase of 17.11% in steps, a 12.76% increase in Very Active minutes, and a 32.52% increase in Moderately Active minutes, when compared to the average for Thursdays, the day of the we%ek on which it occurred.
   - Mother's Day saw an increase of 2.47 in steps and a 16.67% increase in Moderately Active mintues, when compared to the avergage for Sundays, the day of the week on which it occurred but saw a decrease of 14.45% in Very Active minutes.

### Key Findings
- Holidays tend to see some form of activity increase, indicating that when people are spending time together, they're also spending time being active.
- The Department of Health and Human Services recommends that each weak a person gets at least 150 minutes of Moderate Activity or 75 minutes of Vigorous Activity.  The average user in this dataset was Very Active for 149.9 minutes and was Moderately Active for 94.4 minutes per week.  As the combined efforts are meeting the recommended criteria, it appears that the average user is reasonably active.

![https://s-media-cache-ak0.pinimg.com/736x/4a/81/79/4a8179462cfdf39054a418efd4cb743e.jpg](https://i.imgur.com/4VTaYTJ.png)

### Possible Applications
- The existing target audience is already active and meeting government recommended health guidelines. It might be beneficial to target users who do not meet these guidelines. 
- Bellabeat products such as the Leaf and Time have a different aesthetic compared to other fitness trackers such as Fitbit, which means that it is possible to target groups with body issues, who are concerned with social issues such as "fat shaming" by marketing the product as a 'disguised' health tracker. 
- Other products, such as Bellabeat's Spring could be targeted towards the existing, physically fit, client base more heavily, as they are the consumer more likely to be interested in their hydration.
