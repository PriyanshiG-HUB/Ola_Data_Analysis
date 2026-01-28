# 🚖 Ola Booking Data Analytics & Cancellation Analysis

## 📌 Project Overview
This project analyzes **Ola ride booking data** to identify trends in demand, revenue, customer behavior, and ride cancellations.  
The project combines **Python-based data analysis** and **Power BI dashboards** to generate actionable business insights.

---

## 🎯 Objectives
- Analyze booking trends over time  
- Identify high-revenue vehicle categories  
- Understand customer payment behavior  
- Study cancellation patterns and root causes  
- Predict cancellation risk using machine learning  
- Visualize insights using interactive dashboards  

---

## 🗂 Repository Structure

---

## 📁 Folder & File Description

### 📂 data/
| File | Description |
|-----|-------------|
| `Bookings.csv` | Original raw Ola booking dataset |
| `ola_cleaned_data.csv` | Cleaned and processed dataset used for analysis and dashboards |

### 📂 notebooks/
| File | Description |
|-----|-------------|
| `ola_analysis.ipynb` | Python notebook containing data cleaning, EDA, feature engineering, and ML model |

### 📂 visuals/
| File | Description |
|-----|-------------|
| `daily_booking_trend.png` | Line chart showing daily booking trends |
| `revenue_by_vehicle.png` | Bar chart showing revenue by vehicle type |
| `payment_method_distribution.png` | Bar chart showing payment method usage |
| `cancellation_by_vehicle.png` | Stacked bar chart of cancellations by vehicle type |
| `cancellation_by_payment.png` | Bar chart of cancellations by payment method |

### 📂 powerbi/
| File | Description |
|-----|-------------|
| `Ola_Dashboard.pbix` | Power BI file containing interactive dashboards |

---

## 🧹 Data Cleaning & Preprocessing
- Converted date columns to `datetime` format  
- Handled missing values using business logic  
- Removed irrelevant columns  
- Created derived features such as:
  - `is_cancelled` (binary cancellation indicator)

---

## 📊 Exploratory Data Analysis (EDA)
- Daily booking trend analysis  
- Revenue analysis by vehicle type  
- Payment method distribution  
- Ride distance vs booking value analysis  
- Booking status and cancellation distribution  

---

## 📈 Power BI Dashboards

### 📄 Page 1: Booking Overview
- Total Bookings  
- Daily Booking Trend  
- Bookings by Vehicle Type  
- Booking Status Distribution  

### 📄 Page 2: Revenue & Customer Behavior
- Total Revenue  
- Revenue by Vehicle Type  
- Payment Method Distribution  
- Ride Distance vs Booking Value  

### 📄 Page 3: Cancellation Analysis
- Cancellation Rate  
- Cancellations by Vehicle Type  
- Cancellations by Payment Method  
- Driver & Customer Ratings  

---

## 🔍 Key Insights
- ~62% of bookings are successfully completed  
- Prime Sedan generates the highest revenue  
- Majority of rides are short-distance, urban trips  
- Driver-side cancellations are higher than customer-side  
- Cash and low-fare rides show higher cancellation probability  
- Premium services receive higher ratings  

---

## 💡 Business Recommendations
- Improve driver incentive mechanisms  
- Promote digital payments to reduce cancellation risk  
- Optimize driver allocation during peak demand  
- Strengthen premium service reliability  

---

## 🛠 Tools & Technologies
- **Python:** Pandas, Matplotlib, Scikit-learn  
- **Power BI:** Interactive dashboards & DAX  
- **Notebook:** Jupyter / Google Colab  

---

## 🏁 Conclusion
This project demonstrates how **data analytics and machine learning** can be applied to solve real-world operational problems in ride-hailing platforms.  
The insights generated support **data-driven decision-making** to improve efficiency, customer satisfaction, and revenue growth.

---

## 👤 Author
**Priyanshi**  
Data Analytics | Python | Power BI
