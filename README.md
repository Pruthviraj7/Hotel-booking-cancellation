# 🏨 Hotel Booking Analysis

## 📌 Overview
The **Hotel Booking Analysis** project explores trends in hotel reservations, cancellations, and customer behavior using a dataset of **119,390** records with **36 columns**. The analysis aims to identify factors influencing booking cancellations, seasonal trends, and market segment behaviors.

## 📊 Dataset Details
- **Total Records**: 119,390
- **Total Features**: 36
- **Key Columns**:
  - `hotel` (City Hotel, Resort Hotel)
  - `is_canceled` (1 = Canceled, 0 = Not Canceled)
  - `lead_time` (Days between booking and check-in)
  - `arrival_date_*` (Year, Month, Week Number, Day)
  - `stays_in_weekend_nights`, `stays_in_week_nights`
  - `adults`, `children`, `babies`
  - `market_segment` (Booking channel)
  - `deposit_type`, `customer_type`
  - `adr` (Average Daily Rate)

## 🖥️ Exploratory Data Analysis (EDA)

### 🔹 1. Reservation Trends by Month

![image](https://github.com/user-attachments/assets/856a3f56-f439-4d73-b1e4-68b9f1fd710d)

- **July and August** have the highest bookings.
- **January has the highest cancellations**.

### 🔹 2. Average Daily Rate (ADR) by Month

![image](https://github.com/user-attachments/assets/626cb881-8e0f-4d5e-9243-ed82c9adbdd6)

- **ADR spikes in July and drops in September.**
- Seasonal pricing affects cancellation rates.

### 🔹 3. Cancellation Trends by Country

![image](https://github.com/user-attachments/assets/05c9a679-4417-48e9-8bf8-1802fddd64a9)

- **Portugal (PRT) has the highest cancellations** (70.07% of total).
- Other high-cancellation countries: **UK, Spain, France, Germany**.

### 🔹 4. Reservation Status Across Hotel Types

![image](https://github.com/user-attachments/assets/3c6923b0-72eb-4349-bc49-1198d0baf9c9)

- **City hotels have higher cancellations (41.7%) compared to resort hotels (27.9%).**
- City hotels experience more fluctuations in demand.


### 🔹 5. Average Daily Rate Trends for Canceled and Non-Canceled Bookings

![image](https://github.com/user-attachments/assets/91815f6b-847f-48c0-91d2-497d66860fb7)

- **Seasonal trends impact ADR, peaking in summer**.
- **Canceled bookings have higher volatility in ADR values**.


