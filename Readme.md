
---

## 1. 📥 Data Understanding and Preparation

### a. Data Collection
- Downloaded the **Uber Fares Dataset** from Kaggle.
- Loaded into a Pandas DataFrame using Python.

### b. Initial EDA
- Checked dataset structure, data types, column descriptions.
- Assessed missing values and invalid entries.

### c. Data Cleaning
- Removed rows with:
  - Missing or zero GPS coordinates
  - Negative or extremely high fare values
- Converted timestamp fields to proper datetime format
- Exported cleaned data as `uber_cleaned.csv`

---

## 2. 📊 Exploratory Data Analysis (EDA)

### a. Descriptive Statistics
- Calculated:
  - Mean, median, mode
  - Standard deviation
  - Quartiles (Q1, Q3), IQR
- Identified outliers using box plots.

### b. Visual Insights
- **Fare Distribution**: Histogram and box plot for fare amounts
- **Correlation Plots**:
  - Fare amount vs. distance
  - Fare amount vs. pickup hour

---

## 3. 🧠 Feature Engineering

### a. Time-Based Features Extracted:
- `pickup_hour`, `pickup_day`, `pickup_month`, `pickup_weekday`

### b. Categorical Features:
- Created:
  - `is_peak_hour` (True/False)
  - `day_type` (Weekday vs. Weekend)

### c. Final Dataset:
- All new features saved to `uber_enhanced.csv`

---

## 4. 📈 Power BI Data Analysis

### Visualizations Created:
- **Time Analysis**:
  - Line chart: Monthly and daily ride counts
  - Clustered bar: Rides per hour
- **Fare Trend**:
  - Line chart: Average fare by hour/day/month
- **Busiest Periods**:
  - Heatmap showing rides by hour vs. weekday

### Weather Data:
- Not included (no weather data available in dataset)

---

## 5. 📊 Dashboard Creation

### a. Key Dashboard Components:
- **Fare Distribution**:
  - Histogram and box plots for fare amount
- **Ride Duration** (if timestamp difference available):
  - Line chart or KPI for duration trends
- **Time Series**:
  - Temporal trends of rides and fares
- **Geographic Visualization**:
  - Map of pickup and dropoff coordinates

### b. Formatting:
- Consistent color scheme
- Title, labels, and legend applied
- Clean layout with logical grouping of charts

---

## 6. 📝 Final Analytical Report

### 📖  Overview
 In order to identify patterns based on time, location, and distance, this project examines Uber ride fares.  The goal is to use Power BI to deliver visual representations and actionable insights.

### 🔍 Techniques
Gathered raw data from Kaggle, cleaned and prepared it in Python, conducted feature engineering and exploratory analysis, imported the finished dataset into Power BI, and produced interactive visuals to find trends.


### 📊 Analysis
- Most rides occur between **5 PM and 8 PM**, suggesting evening peaks
- **Friday** show higher ride volumes
- Fares increase slightly during **peak evening hours**
- Outliers identified mostly in very short or extremely long trips
- Distance strongly correlates with fare amount (as expected)

### 📌 Results
- Highest number of rides: Fridays, 19 PM
- Highest fare amounts: Long-distance trips during peak times
- Most common trips: Short to medium range within the city
- Geographic clustering observed in central urban areas

### ✅  In conclusion
 Time of day and day of week have a significant impact on both volume and fare amounts, according to the dataset, which clearly shows a pattern in urban ride behaviors.  City center rides and peak hour prices are the most common.

### 💡  Suggestions: 
- Implement dynamic pricing according to day and hour patterns 
- Maximize driver availability during weekends and evenings 
- Employ geographic clustering to enhance ride distribution
- To make predictions for the future, think about combining weather and event data.

 ---

## 📦 Submission Checklist

| Deliverable                        | Status     |
|-----------------------------------|------------|
| Cleaned CSV file (`cleaned_dataset_for_powerbi.csv`) | ✅ |
| Feature-enhanced CSV (`enhanced_uber_data.csv.csv`) | ✅ |
| Power BI Dashboard (`Power_BI_Dashboard.pbix`)      | ✅ |
| Screenshot Proofs                 | ✅ |
| Final Report (This Markdown file) | ✅ |



## 🧠 Author Information

**Name:** *IZABAYO Eloi*  
**ID:** *27131*  
**Institution:** Adventist University of Central Africa (AUCA)  
**Project:** Uber Fares Dataset Analysis  
**Course:** Data Analytics / Power BI  
