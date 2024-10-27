# Hotel Reservation Cancellation Analysis

This project performs an analysis of a hotel reservation dataset to explore key insights related to reservation cancellations. By utilizing powerful data analysis libraries like `pandas`, `matplotlib`, `seaborn`, and `plotly`, the project investigates various aspects of reservation cancellations, such as patterns over time, hotel type comparisons, country-wise cancellations, and the impact of different market segments. The analysis also focuses on the Average Daily Rate (ADR) to provide a deeper understanding of revenue trends between canceled and non-canceled reservations.

## Key Features
- **Data Preprocessing**: Handling missing values, dropping unnecessary columns, and formatting date columns.
- **Exploratory Data Analysis (EDA)**: Visualizing the data using various plots to uncover patterns and trends.
- **Reservation Cancellations**: Insights into cancellation rates for City and Resort Hotels, and across different countries and market segments.
- **Revenue Insights**: Detailed look into the Average Daily Rate (ADR) trends over time and by hotel type, showing differences between canceled and non-canceled bookings.

## Data
The dataset contains detailed information about hotel bookings, including:
- Reservation status (canceled or not canceled)
- Hotel type (City or Resort)
- Average Daily Rate (ADR)
- Reservation dates, room types, and country of the guest

## Visualizations
This project uses several types of visualizations, such as:
- Bar charts for reservation statuses
- Line plots to visualize ADR trends over time
- Count plots for cancellations based on hotel type and market segment
- Pie charts for cancellation rates by country

## Analysis Goals
- Identify the key factors that contribute to hotel reservation cancellations.
- Examine revenue trends for different hotel types.
- Provide actionable insights to help hotels optimize their booking strategies and reduce cancellation rates.

---

### Visualizations

Below are the placeholders for the various charts and plots generated in the analysis. Please replace the placeholders with your actual charts.

---

#### Reservation Status Count
![image](https://github.com/user-attachments/assets/be7ecd00-e9e0-4f56-9671-18f8651be5f6)
## Cancellation Rates in Both Hotels

- **Not Canceled:** 62.86%
- **Canceled:** 37.14%

The data shows that the majority of reservations were not canceled, although a significant portion of bookings were. The bar chart displays the comparison between canceled and non-canceled bookings, highlighting that most reservations remained intact. However, a notable 37% of customers opted to cancel their reservations, which has a meaningful effect on the hotels' financial performance.



---

#### Cancellation Distribution by Hotel Type
![image](https://github.com/user-attachments/assets/f85351ef-995e-4ded-8ab9-aca4836142a5)
## Bookings and Cancellations in City vs Resort Hotels

--------------------------------------------------

- **City Hotels:** Most bookings were made at city hotels.
- **Resort Hotels:** Cancellations are lower in resort hotels compared to city hotels.

The analysis indicates that city hotels receive a higher number of bookings than resort hotels. This difference could be due to resort hotels generally being more expensive than their city counterparts, possibly leading to fewer bookings and cancellations.



---

#### Average Daily Rate (ADR) in City and Resort Hotels Over Time
![image](https://github.com/user-attachments/assets/8392ab35-2633-4550-abd6-7ddcbfbe4365)
## Price Comparison: City vs Resort Hotels

--------------------------------------------------

- **Resort Hotels:** The rates are significantly higher than those of city hotels.
- **City Hotels:** Prices remain relatively stable over time.

The line graph above demonstrates that while the average daily rate for city hotels is generally lower, there are certain days when the prices drop even further. It’s worth noting that resort hotel prices tend to increase during weekends and holidays.



---

#### Reservation Status Per Month
![image](https://github.com/user-attachments/assets/ae2b9e51-527c-478d-bb12-06f254980421)
## Reservation Trends by Month

--------------------------------------------------

- **Peak Booking Months:** May, June, July, and August saw the most reservations.
- **Notable Insights:** A grouped bar graph highlights the fluctuation in reservation statuses across months. August had the highest volume of both confirmed and canceled bookings, while January recorded the fewest confirmed reservations but led in cancellations.


---

#### ADR per Month for Canceled Reservations
![image](https://github.com/user-attachments/assets/012f31ac-60ba-44a9-acea-784cacf169b3)
## Price Influence on Cancellations

--------------------------------------------------

- **Key Observation:** The bar graph demonstrates that cancellations tend to rise when accommodation prices are at their peak and decline when prices are lower. This suggests that pricing plays a significant role in driving reservation cancellations.


---

#### Top 10 Countries Based on Cancellations
![Top 10 Countries for Cancellations](path_to_chart6.png)

---

#### ADR Trend for Canceled and Non-Canceled Reservations
![ADR Canceled vs Not Canceled](path_to_chart7.png)

---

#### ADR Distribution by Room Type and Hotel
![ADR Distribution by Room and Hotel](path_to_chart8.png)

---

You can upload your visualizations in place of the placeholders by replacing the `path_to_chartX.png` with the actual image file paths.
