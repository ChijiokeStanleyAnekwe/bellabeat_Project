# Bellabeat Fitness Tracking Case Study

## Project Overview

<img align="right" width="500" height="250" src="https://bellabeat.com/wp-content/uploads/2023/12/Mask-group-_8_.webp"> 
<a href="https://bellabeat.com/">Bellabeat</a> is a high-tech company that manufactures health-focused smart products for women. Since it was co-founded in 2013 by Urška Sršen and Sando Mur, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. The company has invested in traditional advertising media but focuses extensively on digital marketing. Urška Sršen, the Chief Creative Officer and Cofounder believes that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat's marketing strategy.

## Stakeholders
* Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer

* Sando Mu: Mathematician and Bellabeat’s cofounder

* The Bellabeat marketing analytics team.


## Data Dictionary
Here is a data dictionary describing the variables used in this project:
<a href="https://www.kaggle.com/datasets/dermisfit/bellabeat-data">Click here</a> to download all datasets.

**Daily Activity**
| Variable         | Description                                                |
|------------------|------------------------------------------------------------|
|Id | The unique log id in Fitbit’s systems|
| ActivityDate     | Date value in mm/dd/yyyy format.|
|  TotalSteps | Total number of steps taken.  |
|TotalDistance | Total kilometers tracked.|
|TrackerDistance | Total kilometers tracked by Fitbit device.|
|LoggedActivitiesDistance |Total kilometers from logged activities.|
|VeryActiveDistance | Kilometers travelled during very active activity.|
|ModeratelyActiveDistance | Kilometers travelled during moderate activity.|
|LightActiveDistance | Kilometers travelled during light activity.|
| SedentaryActiveDistance | Kilometers travelled during sedentary activity.|
| VeryActiveMinutes | Total minutes spent in very active activity.|
| FairlyActiveMinutes | Total minutes spent in moderate activity.|
| LightlyActiveMinutes | Total minutes spent in light activity.|
| SedentaryMinutes | Total minutes spent in sedentary activity.|
| Calories | Total estimated energy expenditure (in kilocalories).|

**Hourly Intensity**
| Variable         | Description                                                |
|------------------|------------------------------------------------------------|
|ActivityHour | Date and hour value in mm/dd/yyyy hh:mm:ss format.|
| TotalIntensity | Value calculated by adding all the minute-level intensity values that occurred within the hour|
| AverageIntensity | Average intensity state exhibited during that hour (TotalIntensity for that ActivityHour dividedby 60).|

**Daily Sleep**
| Variable         | Description                                                |
|------------------|------------------------------------------------------------|
|SleepDay | Date on which the sleep event started. (in mm/dd/yyyy hh:mm:ss format) |
|TotalSleepRecords | Number of recorded sleep periods for that day. Includes naps > 60min|
|TotalMinutesAsleep | Total number of minutes classified as being “asleep”.|
|TotalTimeInBed | Total minutes spent in bed, including asleep, restless, and awake, that occurred during a defined sleep record.|
|Id | The unique log id in Fitbit’s system for the sleep record.|

**Weight Log**
| Variable         | Description                                                |
|------------------|------------------------------------------------------------|
|Date | Date and time at which weight was recorded in mm/dd/yy hh:mm:ss format.|
|WeightKg | Weight recorded in kilograms.|
|WeightPounds | Weight in pounds.|
|Fat | Body fat percentage recorded.|
|BMI | Measure of body mass index based on the height and weight in the participant’s Fitbit.com profile.|
|IsManualReport | If the data for this weigh in was done manually (TRUE), or if data was measured and synched directly to Fitbit.com from a connected scale (FALSE)
|LogId | The unique log id in Fitbit’s systems|

## Application
I used python to load, transform and analyze the data, then I used powerpoint to present all deliverables 

## Conclusion 
From the overall analysis;
* The number of steps taken has a positive correlation with amount of calories burned. An increase in number of steps will increase the amount of calories burned.
* The time asleep has a very weak to no correlation with amount of calories burned. Sleeping does not help in burning calories.
* Sedentary time has a negative correlation between steps taken, amount of calories burned and time asleep. Reducing the sedentary minutes is important in staying healthy.
* About 75% of participants did not make use of the weight feature. A sign the participants found it less interesting or difficult to use.
* The participants lightly to very active hours are between 7 a.m. and 10 p.m

**Applying above trend to The Bellabeat's App**
* Notification on daily steps taken: Sending out notifications within the moderate to high intensity activity hours of the app users to remind and encourage them to take at least 8000 steps (in consideration to CDC research results for young and old people). Along with interesting ideas on how users can fit more steps into their routine.
* Notification on daily sleep time: Encouraging users to setup sleeping schedule with respect to their personal routines in order to acheive atleast 8 hours (480 minutes) of recommended sleep time and sending out reminders to encourage them to go bed 3 minutes before their scheduled sleep time since it increases the chances of them falling asleep.
* Should not include weight feature in their product as majority of their users may likely find it uninteresting or very sensitve information to share.
* Tracking and Notification on daily sedentary time: Sending out notification on sedentary time to encourage users to limit sedentary time to 8 hours or less per day

**Marketing strategy**
* The product should be marketed on key features and benefits that users find attractive. (steps taken, burned calories, and sleep )
* Targeted messaging, tailored to resonate with different users segement and their goals
