#  Taj Residency Booking Analysis : Exploratory Data Analysis
![Hotel](https://github.com/user-attachments/assets/b4b7b0d0-63f8-4bcc-af8b-3cabd7bb47b2)

# Objective:-
We are provided with a hotel booking dataset. Our main goal is to perform EDA and draw useful conclusions about general trends in hotel bookings.
# Dataset:-
we are given a hotel booking dataset for a city hotel and a resort hotel.It contains the following features:-
- Hotel: Name of the Hotel(City or Resort)

- is_canceled: whether the booking is canceled or not(0 for no canceled and 1 for canceled)

- lead_time: time between booking transaction and actual arrival

- arrival_date_year: year of arrival

- arrival_date_month: month of arrival

- arrival_date_week_number: week number of arrival date

- arrival_date_day_of_month: day of month of arrival

- stays_in_weekend_nights: No. of weekend nights spent in the hotel

- stay_in_week_night: No. of weeknights spent in a hotel

- adult: No. of adults in a single booking

- children: No. of  children in a single booking

- bibies: No. of babies in a single booking

- meal: Type of meal

- country: Country of customer

- market_segment: what segment via booking

- distribution_channel: via which medium booking was made.

- is_repeated_guest: whether the customer made a booking before this (0 for no and 1 for yes)

- previous_cancellation: No. of the previous canceled booking

- reserved_room_type: room type reserved by customer

- assigned_room_type: room assigned to customer

- booking_changes: No. of booking changes

- agent: Id of agent for booking

- company: Id of company making bookings

- customer_type: Type of customer(Transient ,group)

- required_car_parking_space: No.  of car parking asked

- reservation_status: whether a customer has checked out or canceled

- Total number of rows in data: 119390
- 
- Total number of columns: 32

# Data Cleaning and Feature engineering:-

- Removing Duplicate rows: All duplicate rows are dropped.

- Handling null values: null values in country were dropped and null values in company children and agent were replaced by its mode.

- Converting data type of columns: changed the data types of children,agent, company and reservation_status_date.

- Removing outliers: Outliers are found in adr and lead_time so I handled it.

# Exploratory Data Analysis:-

Performed EDA and tried to answer the following questions:-

- Is not having the reserved room assigned is the reason for booking cancellation?

- Is high lead_time is reason for booking cancellation?

- How many people are reservations made for?

- Which hotel type has most advanced reservation?

- Which distribution channel has the most booking cancellations?

- Which market segment is used for booking hotels and cancellations?

- Which room type generates high adr?

- Which hotel type is the busiest?

- which month is busiest for hotels?

- Which customer type generates more revenue in terms of hotel type and customer type?

Mainly performed by using the Matplotlib and Seaborn library and the following plots are used:-

- Bar plot

- Histogram

- Box plots

- Heatmap

- Violin plot

- Count plot

# Conclusion:-

- City hotels have more bookings than resort hotel. Offer packages and promote booking from the resort hotel

- BB is the most requested food.The hotel should maintain the food quality while offering discounts on other food types to promote other food

- Most of bookings are made from an online platform

- Very few customers are visited again so, hotel can increase repeat bookings by offers.

- Because rooms A and D are the most popular among the customers the hotel should maintain their quality.

- Customer does not want to pre-deposit for reservation. Hotel should promote advance deposits because not only does an advance deposit allow you to recognize revenue faster.

- People book rooms for two people, So encourage the group and family.    





