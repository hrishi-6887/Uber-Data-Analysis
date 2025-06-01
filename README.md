# 🚗 Uber Rides Data Analysis – 2024
![Gemini_Generated_Image_c9sr44c9sr44c9sr](https://github.com/user-attachments/assets/88e9f792-3056-4cc6-a164-90fed3ec7fa9)

## 📌 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on Uber ride data to understand patterns in **ride demand, pickup trends, and temporal dynamics**. The analysis leverages Python libraries like **Pandas, NumPy, Matplotlib,** and **Seaborn** for cleaning, visualization, and insights.

---

## 🎯 Objectives
- Analyze Uber ride trends by **hour, day, and month**.
- Visualize **pickup concentration** by location and time.
- Understand **demand patterns** across different periods.
- Provide actionable insights using graphical visualizations.

---

## 📂 Dataset
The dataset includes Uber ride records with the following features:
- `Date/Time`: Timestamp of the ride
- `Lat`, `Lon`: Latitude and Longitude of pickup location
- `Base`: Base code affiliated with the ride
- Derived features: `Hour`, `Day`, `Month`, and `Weekday` were extracted for temporal analysis.

---

## 🔄 Data Preprocessing
- Converted `Date/Time` to proper datetime format.
- Checked and cleaned null or inconsistent values.
- Converted 'START_DATE' and 'END_DATE' columns to datetime format.
- Extracted date, time, month, and day-type(Morning,afternoon,Night) from 'START_DATE' and 'END_DATE' columns and added these as new columns.

---

## 📊 Key Analysis & Visuals

### 📅 Temporal Trends
- **Hourly Analysis**: Peak demand occurs between 5 PM – 8 PM.
- **Daywise Trends**: Weekends show increased ride activity.
- **Monthly Patterns**: Rides increase towards summer months.

### 📍 Geospatial Insights
- Plotted **pickup locations** using scatter plots to identify busy zones.
- Identified **high-demand clusters** in NYC regions.

### 📈 Visualizations Used
- Histograms, Line plots for time trends
- Heatmaps for correlations
- Countplots for frequency analysis

---

## 💡 Key Insights
- **Evening hours** are the busiest times for Uber rides.
- More than 90% of the rides are for bussiness purpose.
- Ride demand is significantly higher on **Fridays and Saturdays**.
- **Fridays and Saturdays** show the highest volume of trips


## ✅ Recommendations

1. **Optimize Driver Allocation During Peak Hours**  
   Increase driver availability between **5 PM to 8 PM** to reduce wait times and maximize revenue.

2. **Run Seasonal Promotions**  
   Launch **summer-specific offers** or discounts to leverage naturally high demand during those months.

3. **Improve Weekend Support**  
   Ensure **more drivers are available on weekends**, especially Friday and Saturday evenings.

4. **Incorporate Customer Feedback Mechanisms**  
   Introduce feedback loops for riders and drivers to improve **service quality and satisfaction**.

