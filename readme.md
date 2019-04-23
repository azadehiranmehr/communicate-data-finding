# Ford GoBike Trip Data Analysis
## by Azadeh Iranmehr


## Dataset

The dataset, 2017-fordgobike-tripdata.csv, is downloaded from following link and licensed by Ford GoBike. This dataset includes 519,700 trips with 15 features such as locations, time, and user attributes. Before analysis I try tol clean it in a df_clean dataframe.
In this project, our goal is to conduct an exploratory data analysis on Ford GoBike Trip dataset. We will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. This part of the project is gives opportunity to ask questions on data and make discoveries.
Dataset address is :
https://s3.amazonaws.com/fordgobike-data/2017-fordgobike-tripdata.csv


## Summary of Findings

Univariate exploration: There are more trips in the morning and afternoon than the night. Also, there are more trips during the weekdays and less trips during the weekends. There are more subscribers than customers users. The number of trips in male riders is 3 times more than the number of trips in females.  Most of riders are 30 to 40 years old and the duration of trips is around 650 seconds. 

Bivariate exploration: Weekdays have the most trips than weekends. Most trips took place during Sep and Oct when the weather is good enough for riders to ride.  The number of trips gradually increases from August to October and it decreases in the November and December. Biking is definitely correlated with the weather. Subscribers have much more number of trips than customers regardless of their gender, period of the day or day of the week.Subscribers have more median age than customers.Member's age and duration of trips are negatively correlated but this negative correlation is not strong.Median of member age for 4 top more frequent start station are almost the same (about 36 years old)except San Francisco Ferry Building(Harry Bridges Plaza) that has greater median age than others(about 42 years old).Average value of member age for Male is almost 37.90 which is greater than female with average value of 35.1 and for other gender is 36.25.Among all riders, Number of male subscriber is the greatest and number of female customer is the smallest .Subscribers group with rang age of 30-40 years old has the greatest percentage of the total trips(35.86%) and custumers group with rang age of 70-80 years old has the least percentage of the total trips(0.02) .So  we got a feel for the user behavior across gender, age, and their subscription status. 

Multivariate exploration: separating user types, customers and subscribers, gives more insights. Customers like to bike during the weekend and in the summer. Also, the number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers. Both of them have the longest trips at night and in December. I am guessing because of holiday seasons but not sure about why night trips are longer so still need more data to prove my point.
Start time 12:00,13:00,14:00, 15:00 and 16:00 on weekends have greatest number of mean trip count and start time 8:00 on Monday is the greatest number of mean trip count during the week. The trip duration for Customers is greater than Subscribers.It does not depend on the days of the week and gender.Male subscribers have maximum mean of age and female customers have minimum mean of age.


## Key Insights for Presentation

The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. 