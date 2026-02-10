# Uber Rides Data Analysis — 2024

This repository contains an end-to-end exploratory data analysis of **Uber ride-hailing trips for 2024**. The goal of this case study is to uncover patterns in **demand, cancellations, ride metrics, revenue, and customer behavior** to support data-driven decision making for ride-sharing operations.

---

## 📌 Project Overview

Ride-hailing platforms generate large amounts of data every day. This project analyzes approximately **150,000 Uber ride trips** to:

- Understand travel demand patterns  
- Explore cancellation behavior  
- Analyze revenue and ride characteristics  
- Identify trends across time of day, days of the week, and geographic context  

The insights from this analysis can help improve:
- Operational efficiency
- Customer satisfaction
- Revenue optimization
- Driver experience and performance  

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `README.md` | Project overview and documentation |
| `UberDataAnalysis.ipynb` | Jupyter Notebook containing the full analysis workflow |
| `ncr_ride_bookings.csv` | Raw dataset used for analysis |
| `An Exploratory Data Analysis of Uber.pdf` | Well documented PDF version of the analysis |

---

## 🔗 Link
Dataset Source: [Uber Ride Dataset 2024]([url](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard))

---

## 📊 Data Description

The dataset used in this project includes detailed information about Uber rides, with key fields such as:

| Column | Description |
|--------|-------------|
| `Booking_ID` | Unique ID for each ride booking |
| `Date` | Date of the ride |
| `Time` | Time of the ride |
| `Booking_Status` | Indicates if a ride was completed or cancelled |
| `Customer_ID` | Unique identifier for the customer |
| `Vehicle_Type` | Category of vehicle used (e.g., Sedan, eBike) |
| `Pickup_Location` | Start location of the ride |
| `Drop_Location` | Destination of the ride |
| `Booking_Value` | Fare amount for the ride |
| `Ride_Distance` | Distance of the trip in kilometers |
| `Driver_Ratings` | Rating given to the driver |
| `Customer_Rating` | Rating given by the customer |

> Note: This is a high-level summary. Refer to the notebook for full column descriptions and formats.

---

## 📌 Key Insights


- **Demand Patterns:** Ride requests vary by time of day and day of week, with peaks during commute hours and weekends.  
- **Cancellation Trends:** A significant fraction of bookings are cancelled; customer and driver cancellations show distinct patterns.  
- **Revenue & Booking Analysis:** Booking values and distances reveal insight into pricing and ride durations.  
- **Ratings Insights:** Customer and driver ratings provide a view of service quality and satisfaction.


---

## 🧠 Methodology

The analysis workflow includes:

1. **Data Cleaning & Preprocessing:**  
   - Handled missing values and invalid entries  
   - Converted data types  
   - Cleaned duplicate records  

2. **Exploratory Data Analysis (EDA):**  
   - Summary statistics  
   - Time-based trends  
   - Cancellations and ride patterns  
	
---

## 🛠 Tools Used

- **Python**  
- **pandas & NumPy** — Data manipulation  
- **Matplotlib & Seaborn** — Visualization  
- **Jupyter Notebook** — Reproducible analysis

---

## 📬 Contact

For questions or feedback, feel free to connect:

**Ekta Mangar** – Data Analyst & Project Author
