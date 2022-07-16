# Airline-Delay-Analysis-Capstone-Project-for-30daysoflearning-
This is my submission for my capstone project. It includes in it a report of exploratory and diagnostic analysis on airline delays

# Introduction:
The 30 days of learning is an initiative stated by Olanrewaju Oyinbooke (on Twitter @theOyinbooke), a Microsoft senior cloud advocate and his team wherein they sought to empower students with in demand skills in technology.
The program has three tracks which are:
1. Data Analysis with Power BI
2. Data Science and Machine Learning
3. Power platform and low or no-code development
To follow our learning track on Twitter, you can simply use the hashtag #30daysoflearning. If you wish to learn any of these, you may register for the program here.
After 22 days of learning data analysis we were given a project which includes the airline Delay project, to which tbis submission is been made.

According to a 2010 report made by the US Federal Aviation Administration, the economic price of domestic flight delays entails a yearly cost of 32.9 billion dollars to passengers, airlines and other parts of the economy.
More than half of that amount comes from the pockets of passengers who not only lose time waiting for their planes to leave, but they also miss connecting flights, spend money on food and have to sleep on hotel rooms while they're stranded.
This report seeks to explore the possible Impacts of this delays and also some possible causes.
![flight](https://user-images.githubusercontent.com/88923136/179361143-a5d01ac5-2094-455f-9e38-de6049f49599.png)


# Problem Statement:
This project seeks to answer the following questions:
1. What has been the history of delayed flights?
2. Any identified pattern with the delayed flights?
3. What could be the possible causes of flight delay?
4. What possible recommendations can help solve this problem?

# Data Sourcing: 
The original dataset was purposed for predicting whether a given flight will be delayed, given the information of the scheduled departure.
However, my task is to understudy this data and tell a story about the entire flight experience.
The data is available here.

# Data Transformation:
The only Transformation made to the data was by changing the data type for the delay column to from numbers to logical data (true/false).
After the transformation of the data, the data now looks like the image below: 

![data transformation_LI](https://user-images.githubusercontent.com/88923136/179361369-b9fe6fcc-38ff-485c-9e5e-585ea81f41e1.jpg)

# Data Analysis and Report Building: 
1. Firstly, I analyzed the data to check for the history of flights delay. I built a chart showing the top 5 airlines with highest flight frequency.

![Top 5 airlines](https://user-images.githubusercontent.com/88923136/179361214-2f398602-fc70-455d-b01d-d2e872729d75.png)

2. Then I analyzed the data to find out the frequency of flights per day.

![frequency of flights per day](https://user-images.githubusercontent.com/88923136/179361231-245c6a8c-dc46-4fbc-9e45-246b28eb3bda.png)

3. Thereafter, I analyzed the data to find out the Top 5 airlines covering the longest distances and its correlation with whether the flight becomes delayed or not. 

![Distance and length](https://user-images.githubusercontent.com/88923136/179361262-eb58f3c4-edef-491d-a014-d692abdd50ce.png)

4. I then added a slicer with which users can filter the visualizations per day. 

![slicer](https://user-images.githubusercontent.com/88923136/179361271-0edfd4cd-663d-43c2-a876-c00787b7ee33.png)

# Findings and Recommendations: 
After analyzing and building my visualizations the following are my findings and recommendations:
1. Flights are more during the midweek, specifically on Wednesdays and are least on Fridays and weekends.
2. The airlins with higher flight frequency also have high number of delays, even though they covered lesser distance.
3. There is a negative correlation between distance covered by flights and delay. This negative correlation may mean that the longer the distance to be covered by the airline, the more they avoid delays and the distance to be covered by the airline, the more they are relaxed and accommodate delays in flights.
4. Delays were more associated with the popularity of the airline, this may man that the delays are due to waiting for and on-boarding of Passengers.

This is a screenshot of the completed report, and the file can be downloaded above, to interact with the dashboard.

![full report](https://user-images.githubusercontent.com/88923136/179361281-d0282935-8b6b-42b7-b94e-47d4ec488839.png)
