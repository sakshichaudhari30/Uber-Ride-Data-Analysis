# 🚕 Uber Ride Analytics using EDA

## 📌 Project Overview

This project analyzes Uber ride booking data using **Python, Exploratory Data Analysis (EDA), and SQL**.

The main goal is to understand ride patterns, vehicle usage, cancellations, booking values, and ride distances.

---

## 🎯 Objectives

* Clean and prepare the Uber dataset
* Analyze booking and cancellation patterns
* Analyze vehicle types
* Study booking value and ride distance
* Identify outliers and correlations
* Use SQL to answer business questions
* Generate useful insights from the data

---

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* MySQL
* SQLAlchemy
* PyMySQL
* Jupyter Notebook

---

## 📂 Dataset

**Dataset:** NCR Ride Bookings

* **150,000 rows**
* **21 columns**

The dataset contains information about:

* Booking status
* Vehicle type
* Booking value
* Ride distance
* Pickup and drop locations
* Cancellation reasons
* Ratings
* Payment method

---

## 🧹 Data Cleaning

The following steps were performed:

* Checked data types
* Checked missing values
* Identified `"null"` values
* Removed duplicate records
* Checked invalid values
* Detected outliers using the **IQR method**

After removing **1,233 duplicate records**, the dataset contained **148,767 records**.

---

## 📊 Analysis & Visualizations

The project includes analysis of:

* **Vehicle Type**
* **Booking Status**
* **Cancellations**
* **Booking Value**
* **Ride Distance**
* **Correlation between numerical variables**

### Vehicle Type Analysis

<img width="1167" height="775" alt="Screenshot 2026-10-03 123036" src="https://github.com/user-attachments/assets/2b3f55ec-c9ce-4ac0-8447-650d7e611c8d" />

### Cancellation Analysis

<img width="727" height="595" alt="image" src="https://github.com/user-attachments/assets/1d6556e5-a949-4628-8f21-b471c945ca18" />

### Correlation Heatmap 
<img width="1162" height="835" alt="image" src="https://github.com/user-attachments/assets/2d8eb5d7-ddb5-4848-bb54-67f0c63666f7" />


---

## 🗄️ SQL Analysis

MySQL was used to analyze the cleaned data and answer business questions such as:

* Which vehicle types have more bookings?
* How many rides were completed or cancelled?
* What are the common cancellation reasons?
* What is the average booking value?
* What is the average ride distance?

---

## 💡 Key Insights

* **93,000** bookings were completed.
* **27,000** bookings were cancelled by drivers.
* **10,500** bookings were cancelled by customers.
* Auto had **37,419 bookings**.
* Average Booking Value was approximately **₹478.12**.
* Average Ride Distance was approximately **24.34 km**.
* Duplicate records and potential outliers were identified during data cleaning.

---

## 📁 Project Structure

```text
Uber-Ride-Data-Analysis/
│
├── images/
│   ├── vehicle_analysis.png
│   ├── cancellation_analysis.png
│   ├── booking_value.png
│   └── correlation_heatmap.png
│
├── uber_ride_analysis.ipynb
├── ncr_ride_bookings.csv
└── README.md
```

---

## 👩‍💻 Author

**Sakshi Chaudhari**

Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Pandas | NumPy | MySQL | EDA | Analytics
