# Data Centric Programming Assignment 2026

Name: Daniel O'Sullivan

Student Number: A00034166

# Assignment Proposal
My assignment will be collcting data on playing guitar and bass. I will record the date, time of day, minutes played, if I learned a new song or made one of my own, how many songs were played.


# Questions
1. Which days do i get the most steps in on
2. How much does the active time differ between days
3. How does my most active hour change each day 
# Data Dictionary

| Column Name | Data Type | Units | How It Is Measured |
|---|---|---|---|
| Date | Date | DD-MM-YYYY | The date on which the activity data was recorded. |

| Steps | Integer | Steps | The total number of steps recorded by the activity tracker during the day. |

| Active Time | Integer | Minutes | The total time spent performing physical activity, recorded by the activity tracker. |

| Activity Calories | Integer | Kilocalories (kcal) | The estimated calories burned through physical activity during the day, as reported by the tracker. |

| Total Calories | Integer | Kilocalories (kcal) | The estimated total calories burned during the day, including activity and resting energy, as reported by the tracker. |

| Distance while active | Float | Kilometres (km) | The total distance travelled during recorded activity, as reported by the tracker. |

| Most Active Hour | Integer | Hour (0–23) | The hour of the day with the highest recorded activity, using the 24-hour clock. |

| Day Type | String (Categorical) | None | Classifies the day as a weekday or weekend based on the date. |

