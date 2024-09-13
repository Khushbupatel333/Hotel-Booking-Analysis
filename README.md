#  Taj Residency Booking Analysis : Exploratory Data Analysis
![Hotel](https://github.com/user-attachments/assets/b4b7b0d0-63f8-4bcc-af8b-3cabd7bb47b2)

# Objective:-
We are provided with hotel booking dataset. Our main goal is to perform EDA and draw useful conclusion about general trends in hotel bookings.
# Dataset:-
we are given hotel booking dataset for a city hotel and resort hotel.It contains the following features:-
- Hotel: Name of the Hotel(City or Resort)

- is_canceled: weather the booking is canceled or not(0 for no canceled and 1 for canceled)

- lead_time: time between booking transaction and actual arrival

- arrival_date_year: year of arrival

- arrival_date_month: month of arrival

- arrival_date_week_number: week number of arrival date

- arrival_date_day_of_month: day of month of arrival

- stays_in_weekend_nights: No. of weekends night spend in hotel

- stay_in_week_night: No. of week nights spent in hotel

- adult: No. of adult in single booking

- children: No of  children in single booking

- bibies: No. of babies in single booking

- meal: Type of meal

- country: Country of customer

- market_segment: what segment via booking

- distribution_channel: via which medium booking was made.

- is_repeated_guest: weather the customer made booking before this (0 for no and 1 for yes)

- previous_cancellation: No. of previous cancelled booking

- reserved_room_type: room type reservedby customer

- assigned_room_type: room assigned to customer

- booking_changes: No. of booking changes

- agent: Id of agent for booking

- compony: Id of compony making bookings

- customer_type: Type of customer(Transient ,group)

- required_car_parking_space: No of car parking asked

- reservation_status: weather a customer has checked out or canceled

- Total number of rows in data: 119390
- 
- Total number of columns: 32

# Data Cleaning and Feature engineering:-

- Removing Duplicate rows: All duplicate rows are dropped.

- Handling null values: null values in country were dropped and null values in compony children and agent were replaced by its mode.

- Converting data type of columns: changed the data types of children,agent,compony and reservation_status_date,

- Removing outliers: Outliers are found in adr and lead_time so handled it.

# Exploratory Data Analysis:-

Performed EDA and tried to answer the following questions:-

- Is not having the reserved room assign is reason for booking cancellation?

- Is high lead_time is reason for booking cancellation?

- How many people are reservation made for?

- Which hotel type has most advance reservation?

- Which distribution channel has most booking cancellation?

- Which market segment is used for booking hotel and cancellation?

- Which room type generate high adr?

- Which hotel type is busiest?

- which month is busiest for hotels?

- Which customer type generate more revenue in term of hotel type and customer type?

Mainly perfomed by using the Matplotlib and Seaborn library and the following plots are uesd:-

- Bar plot

- Histogram

- Box plots

- Heatmap

- Violin plot

- Count plot

# Conclusion:-

- City hotels have more booking than the resort hotel.Offer packeage and promote booking fro resort hotel

- BB is most requested food.The hotel should maintain the food quality whilw offering discount on other food type to promote other food

- Most of booking are made from online plateform

- Very few customers are visited again so,hotel can increase repeate booking by offers.

- Because room A and D are most popular among the customer the hotel should maintain theri quality.

- Customer do not want ot pre-deposit for reservation.Hotel should promote advance deposit because not only does in advance deposit allow you to recognize revenue faster.

- People book rooms for rwo people,So encourage the group and family.    
