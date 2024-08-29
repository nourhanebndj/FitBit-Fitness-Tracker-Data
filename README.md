# 🏋️ Fitbit Fitness Tracker Analysis

## 📄 Project Description

This project involves analyzing data collected from a survey distributed via Amazon Mechanical Turk between December 3rd and 5th, 2016. The dataset includes minute-level data on physical activity, heart rate, and sleep monitoring from 30 Fitbit users who consented to submit their personal tracker information. The purpose of this analysis is to gain insights into the participants' daily activity patterns, caloric expenditure, and tracking behaviors. The data reflects the variability in activity levels and behaviors due to the different types of Fitbit devices used and individual tracking preferences.

## 📊 Results

### 1. 📉 Pie Chart (SedentaryMinutes, LightlyActiveMinutes, FairlyActiveMinutes, VeryActiveMinutes)

![Pie Chart](https://github.com/nourhanebndj/FitBit-Fitness-Tracker-Data/blob/main/pie%20chart.png)

- **🛋️ SedentaryMinutes**: The analysis reveals that the majority of the time is spent in sedentary activities, accounting for 83.3% of the total minutes. This indicates a largely inactive lifestyle among the participants.
  
- **🚶‍♂️ LightlyActiveMinutes**: Lightly active minutes make up 14.2% of the total time. While this is significantly smaller than the sedentary minutes, it still represents a notable portion of the participants' daily activities.
  
- **🏃‍♂️ FairlyActiveMinutes & VeryActiveMinutes**: Both fairly active and very active minutes are minimal, each contributing only about 1.4% to the total. This further suggests that the participants engage in limited physical activity.

### 2. 🔥 Scatter Plot (Calories by Hours)

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/nourhanebndj/FitBit-Fitness-Tracker-Data/blob/main/Calories%20by%20Total%20Steps.png" alt="Scatter Plot Calories by Steps" width="45%">
  <img src="https://github.com/nourhanebndj/FitBit-Fitness-Tracker-Data/blob/main/Calories%20by%20Total%20Hours.png" alt="Scatter Plot Calories by Hours" width="45%">
</div>

- **⏳ Calories vs. Hours**: The scatter plot shows the relationship between calories burned and hours of activity. Data points are color-coded, likely indicating the intensity of the activities.
  
- **🔗 Median Lines**: The plot features a horizontal line representing the median of calories burned (~2000 calories) and a vertical line representing the median of hours spent on activities. 

- **📈 Data Distribution**: The data appears clustered, showing higher calorie burns with increasing hours of activity. However, there is considerable variability. Some data points indicate high calorie burns at low hours, which could represent outliers or instances of high-intensity bursts of activity.

### 3. 🪜 Scatter Plot (Calories by Total Steps)

![Bar Plot](https://github.com/nourhanebndj/FitBit-Fitness-Tracker-Data/blob/main/Frequency%20by%20Day%20of%20the%20Week.png)

- **📊 Activity Frequency**: This bar plot illustrates the frequency of an activity (likely the tracking or recording of data) by the day of the week.
  
- **🗓️ Weekly Pattern**: The highest frequencies are observed on Friday, Saturday, Sunday, and Monday, with a noticeable drop on Wednesday and Thursday. This pattern suggests that the participants may be more active or more consistent in data recording on weekends and at the beginning of the week, with a potential decline in activity mid-week.

## ✅ Conclusion

The analysis indicates that the participants predominantly lead a sedentary lifestyle with limited periods of light to moderate physical activity. There is a positive correlation between the number of steps taken and the calories burned, although the efficiency of calorie burning varies among participants. The activity tracking or engagement appears to be more consistent during weekends and the start of the week, suggesting a possible decline in activity mid-week. These insights could be useful for designing interventions aimed at promoting more consistent physical activity and reducing sedentary behavior among the participants.


## Kaggle Link
You can find the dataset used in this project on Kaggle via the following link:
[Kaggle Weather Data](https://www.kaggle.com/code/nourhanebndj/fitbit-fitness-tracker-data) 
