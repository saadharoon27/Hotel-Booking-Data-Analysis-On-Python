![banner](Assets/Banner.jpg)

# Hotel-Booking-Data-Analysis-On-Python
***High cancellation rates at City Hotel and Resort Hotel are causing revenue loss and inefficiency. This analysis focuses on booking cancellations and other non-business-related factors impacting yearly revenue.***

## Author
- [@saadharoon27](https://github.com/saadharoon27)

## Table of Contents
- [Business Problem](#business-problem)
- [About The Dataset](#about-the-dataset)
- [Project Assumptions](#project-assumptions)
- [Research Questions](#research-questions)
- [Hypothesis](#hypothesis)
- [Explore The Notebook](#explore-the-notebook)
- [Research Findings](#research-findings)
- [Suggestions](#suggestions)

## Business Problem
In recent years, **City Hotel** and **Resort Hotel** have seen high cancellation rates. Each hotel is facing a number of issues as a result, including fewer revenues and less than-ideal hotel room use. Consequently, lowering cancellation rates is both hotels' primary goal in order to increase their efficiency in generating revenue and offer thorough business advice to address this problem. <br>

The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this report.

## About The Dataset

[**Hotel Booking Dataset**](https://www.kaggle.com/datasets/saadharoon27/hotel-booking-dataset)

| **Column Name**                 | **Description**                                                                            |
|-----------------------------|-----------------------------------------------------------------------------------------------|
| **hotel**                   | Type of hotel (City Hotel or Resort Hotel).                                                    |
| **is_canceled**             | Binary value indicating whether the booking was canceled (1) or not (0).                      |
| **lead_time**               | Number of days between the booking and arrival date.                                           |
| **arrival_date_year**       | The year of the arrival date.                                                                 |
| **arrival_date_month**      | The month of the arrival date.                                                                |
| **arrival_date_week_number**| Week number of the arrival date.                                                              |
| **arrival_date_day_of_month**| Day of the month of the arrival date.                                                         |
| **stays_in_weekend_nights**  | Number of weekend nights (Saturday or Sunday) the guest stayed.                                |
| **stays_in_week_nights**     | Number of weekday nights the guest stayed.                                                    |
| **adults**                   | Number of adults.                                                                             |
| **children**                 | Number of children.                                                                           |
| **babies**                   | Number of babies.                                                                             |
| **meal**                     | Type of meal booked.                                                                         |
| **country**                  | Country of origin.                                                                           |
| **market_segment**           | Market segment designation.                                                                  |
| **distribution_channel**     | Booking distribution channel.                                                                |
| **is_repeated_guest**        | Binary value indicating whether the guest is a repeated guest (1) or not (0).                  |
| **previous_cancellations**   | Number of previous booking cancellations.                                                     |
| **previous_bookings_not_canceled**| Number of previous bookings not canceled.                                                  |
| **reserved_room_type**       | Type of room reserved.                                                                       |
| **assigned_room_type**       | Type of room assigned.                                                                       |
| **booking_changes**          | Number of changes made to the booking.                                                       |
| **deposit_type**             | Type of deposit made for the booking.                                                         |
| **agent**                    | ID of the travel agency that made the booking.                                                |
| **company**                  | ID of the company/organization that made the booking.                                         |
| **days_in_waiting_list**     | Number of days in the waiting list before the booking was confirmed.                           |
| **customer_type**            | Type of customer (e.g., transient, contract, group).                                          |
| **adr**                      | Average Daily Rate, indicating the average room rate per night.                                |
| **required_car_parking_spaces**| Number of car parking spaces required.                                                      |
| **total_of_special_requests** | Number of special requests made by the guest.                                                |
| **reservation_status**       | Reservation last status (e.g., Check-Out, Canceled).                                          |
| **reservation_status_date**  | Date at which the last status was set.                                                        |
| **name**                    | Name of the guest.                                                                           |
| **email**                   | Guest's email address.                                                                      |
| **phone-number**            | Guest's phone number.                                                                       |
| **credit_card**             | Type of credit card used for booking.                                                        |

## Project Assumptions

- **No unusual occurrences** between 2015 and 2017 will have a substantial impact on the data used.
- The information is still current and can be used to analyze a hotel’s possible plans in an efficient manner.
- There are **no unanticipated negatives** to the hotel employing any advised technique.
- The hotels are not currently using any of the suggested solutions.
- The **biggest factor** affecting the effectiveness of earning income is booking cancellations.
- Cancellations result in **vacant rooms** for the booked length of time.
- Clients make hotel reservations the same year they make cancellations.

## Research Questions
**1.** _What are the variables that affect hotel reservations cancellations?_ <br>
**2.** _How can we make hotel reservations cancellations better?_ <br>
**3.** _How will hotels be assisted in making pricing and promotional decisions?_

## Hypothesis
**1.** _More cancellations occur when prices are higher._ <br>
**2.** _The majority of clients are coming from offline travel agents to make their reservations._

## Explore The Notebook
To explore the notebook file click [**here**](https://github.com/saadharoon27/Hotel-Booking-Data-Analysis-On-Python/blob/cef94c56d17124528ecf66052d9f41a786551233/Hotel%20Data%20Analysis.ipynb)

## Research Findings![image](https://github.com/saadharoon27/Hotel-Booking-Data-Analysis-On-Python/assets/147087623/a4427d7b-64a5-4e25-a09d-df1e4aecdaac)

