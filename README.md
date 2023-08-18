# Hotel Booking Demand

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.  

This article on medium explains the entire the process  
[Exploratory Data Analysis of the Hotel Booking Demand with Python](https://medium.com/@aaqibqs/exploratory-data-analysis-of-the-hotel-booking-demand-with-python-200925230106)


## Table of Content
- [Motivation](#Motivation)
- [Tools and Libraries Used](#Tools-and-Libraries-Used)
- [Files](#Files)
- [Result](#Result)
- [Dataset Information](#Dataset-Information)
- [Acknowledgements](#Acknowledgements)

## Motivation

### We have tried to answer the following Questions
1. How Many Booking Were Cancelled?
2. What is the booking demand ratio between Resort Hotel and City Hotel?
3. What is the percentage of hotel booking demand for each year?
4. Which is the most demanded month for hotel?
5. From which country most guest come?
6. How Long People Stay in the hotel?
7. Which was the most booked accommodation type (Single, Couple, Family)?
8. Which was most demanded meal in hotels?
9. Which was most demanded week of the month?
10. Which was most demanded room type ?
11. Which room type was mostly demandly reserved ?
12. Which was most demanded meal in hotels?

### After that we made the predictive model to predict whether the booking will be cancelled or not

**We will:**
- Perform the features Selection to select only relevant features
- Tranform the Data (Categorial to Numerical)
- Split the data (Train Test Split)
- Model the data (Fit the Data)
- And finally Evaluate our model

## Tools and Libraries Used
We have used Python 3 to its following packages:
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- pycountry

## Files
This repository contains two files other than readme file

**hotel_data:** this file contain x,y-test.csv,model and etc.
**Hotel_Booking_demand_Model_training,prediction.ipynb:** Jupyter Notebook file contains all the python code.
**EDA-hotel_bookings_demand** eda, documentation and visualization 
**hotel_bookings.csv:** Our dataset file
**split_rawdata_test,train.ipynb:**  Jupyter Notebook file contains all the python code,split the whole data into train and test for prediction 

**Dataset contains following features:**
1. hotel
2. is_canceled
3. lead_time
4. arrival_date_year
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_week_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellations
19. previous_bookings_not_canceled
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent
25. company
26. days_in_waiting_list
27. customer_type
28. adr
29. required_car_parking_spaces
30. total_of_special_requests
31. reservation_status
32. reservation_status_date


## Result

We learned that
1. Almost 28% of bookings were cancelled and 72% were not cancelled.
2. More than 60% of the population booked the City hotel.
3. More than double the rate of bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year
4. Most bookings were made from July to August. And the least bookings were made at the start and end of the year.
5. Portugal-34%, the UK-16%, and France-9% are the top countries from most guests come, more than 59% come from these 3 countries.<br>
6. Most people stay for one, two, or three.<br>
   -> For Resort hotel, the most popular stay duration is three, two, one, and four days respectively.<br>
   -> For City hotel, most popular stay duration is one, two, seven(week), and three respectively<br>
7. Couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly<br>
8. that week number 4 has the high bookings compered to other weeks and its the last week of the month.<br>
9. Most of the bookings were made through TA/TO (Travel Agent/Tour Operators).<br>
10. In City Hotel 35000+ and while in Resort Hotel 20000+ guests visited more than once which shows the overall service of the city hotels were good.<br>
11. Room Type A was mostly reserved and demanded in both the hotels.<br>
12. That "BB" is the most demanded meal package of both hotels.<br>

<p float="left" align="middle">  
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/59d16cb5-1085-4ed2-a717-3e058795de98" width="400"/>
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/8ddaa7bf-8e27-4a8b-aea1-47aa1327b5ba" width="400" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/2149997d-bc54-4b4a-985c-f7d291b00fc0" width="400" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/8a11dad1-f208-4b1d-ab4f-73cf1fd6dbfb" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/0d6c45a1-8393-45a4-9027-e740eb7180fc" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/22357457-2142-4a17-bc43-6b0fee9e0ff5" width="400" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/b8ea840b-9ffc-4b88-8e4f-1a31000bd8c6" width="400" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/f6e13278-6e21-40fe-813c-c25c16d352ba" width="400" />
  <img src="https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/bc52c086-ffb5-4c39-9fc2-a5e574250958" width="400" />
 </p>
## Project Demonstration Video


https://github.com/Manikandandurai-git/hotel-bookings-demand-project/assets/119742683/8bf9cb93-1f0f-4647-b4a4-f0c890ab0195




## Dataset Information:  
Data was posted on Kaggle by Jesse Mostipak.
It is available to download Here:
https://www.kaggle.com/jessemostipak/hotel-booking-demand


#### Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.
