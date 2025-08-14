# skillcraft_task4_Accident-Data-Analysis-Visualization
# Accident Data Analysis & Visualization

## 📌 Description
This project analyzes a road accident dataset and creates various visualizations to understand accident patterns based on severity, weather, time, and other factors.  
The goal is to uncover insights that can help improve road safety and traffic management.

## 📂 Dataset
- **File:** `accidentdata.csv`
- **Source:** Any road accident dataset (e.g., US Accidents Dataset from Kaggle)
- **Important Columns Used:**
  - `Severity` – Accident severity level
  - `Weather_Condition` – Weather during accident
  - `Start_Time` – Date and time of accident
  - `Sunrise_Sunset` – Day/Night indicator
  - `Visibility(mi)` – Visibility in miles

## 🧹 Data Preprocessing
- Converted `Start_Time` to datetime format.
- Extracted:
  - `Hour` – Hour of the day accident occurred.
  - `DayOfWeek` – Day of the week accident occurred.
- Created output folders to store plots.

## 📊 Visualizations Generated
The following charts are saved in **`outputs/plots`**:

1. **Accidents by Severity Level**  
   File: `accidents_by_severity.png`
2. **Top 10 Weather Conditions in Accidents**  
   File: `accidents_by_weather.png`
3. **Accidents by Hour of Day**  
   File: `accidents_by_hour.png`
4. **Accidents by Day of the Week**  
   File: `accidents_by_day.png`
5. **Day vs Night Accidents**  
   File: `accidents_by_sunrise_sunset.png`
6. **Correlation Heatmap (Severity, Visibility, Hour)**  
   File: `correlation_heatmap.png`

## ▶️ How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
