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
Dataset Source: [Uber Ride Dataset 2024](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard)

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

## 📊 Key Insights


- Only 62% of rides are completed, with driver cancellations (47.4% of all failed rides) causing nearly half of all failures — the biggest reliability gap.  
- Nearly 90% of customer cancellations are driven by four reasons(Change of plans, Driver asked to cancel, Driver not moving toward pickup, and Wrong address represent). Most notably, "Driver asked to cancel" and "Driver not moving," indicating that cancellations are often forced by supply-side behavior rather than customer intent.  
- Peak-hour congestion (9–11 AM, 3–9 PM) drives the most cancellations due to supply–demand mismatch and pickup location issues.  
- A few hotspots show high bookings but low completion, indicating operational inefficiencies.
- Auto fleet delivers the highest completions and revenue, while short trips generate better revenue efficiency than long trips.
- There is a 90%+ drop in revenue-per-km between short and long-distance trips.

## 💡 Recommendations

- Reduce cancellations with driver incentives and accountability tracking.
- Improve peak-hour supply through demand forecasting and pre-positioning drivers in high-traffic zones.
- Fix pickup accuracy using better GPS mapping and recommended pickup points.
- Prioritize the expansion and maintenance of the Auto fleet.
- Introduce in-app vehicle health checks (AC, tires, battery) to reduce "Vehicle Breakdown" cancellations, which peak during high-demand hours.
- Optimize the distance-based fare scaling and pricing to improve long-trip profitability.

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
