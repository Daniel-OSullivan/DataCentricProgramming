# Data Centric Programming Assignment 2026

Name: Daniel O'Sullivan

Student Number: A00034166

# Assignment Proposal
My assignment will be collcting data on playing guitar and bass. I will record the date, time of day, minutes played, if I learned a new song or made one of my own, how many songs were played, if it was actual practice or just riffing


# Questions
1. Which days do i get the most practice in on
2. How does learning a new song or creating an original affect productivity and enjoyment
3. What time of day is mose common/most productive
# Data Dictionary

| Column Name | Data Type | Units | How It Is Measured |
|---|---|---|---|
| Date | Date | YYYY-MM-DD | The date on which the activity data was recorded. |
|---|---|---|---|
| Time of Day | String (Categorical) | None | The part of the day the session took place in: morning, afternoon or evening.|
|---|---|---|---|
| Day Type | String (Categorical) | None | The type of day: Work, college, or rest day |
|---|---|---|---|
| Instrument | String (Categorical)	| None | The instrument played during the session: guitar or bass.|
|---|---|---|---|
| Minutes Played | Integer | Minutes | The total time spent playing during the session, timed by me with a stopwatch or clock. |
|---|---|---|---|
| New Song or Original | String (Categorical) | None | Whether I learned a new song, wrote an original piece, or did neither during the session.|
|---|---|---|---|
| Songs Played | Integer | Songs | The number of songs I played all the way through during the session, counted by me. |
|---|---|---|---|
| Practice or Riffing | String (Categorical) | None | Whether the session was structured practice or casual riffing, as judged by me at the time.|
|---|---|---|---|
| Productivity | Integer | Rating (1-5) | My own rating of how productive the session felt, where 1 is not productive at all and 5 is extremely productive. |
|---|---|---|---|
| Enjoyment	| Integer | Rating (1-5) | My own rating of how much I enjoyed the session, where 1 is not enjoyable at all and 5 is extremely enjoyable. |
