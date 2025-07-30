# ✈️ Flight Delay Analysis – Excel Project

## 📊 Overview
This project analyzes U.S. domestic flight performance using Excel, focusing on delays, cancellations, airport connectivity, airline efficiency, and weather-related impacts. The dataset covers key variables like departure/arrival times, delay reasons, airline codes, and flight dates.

## 📁 Dataset Features
- **Variables**: YEAR, MONTH, DAY, AIRLINE, FLIGHT_NUMBER, ORIGIN_AIRPORT, DESTINATION_AIRPORT, SCHEDULED_DEPARTURE, DEPARTURE_DELAY, ARRIVAL_DELAY, CANCELLED, etc.
- **Size**: 500K+ rows (simulated)
- **Source**: FAA and BTS (sample format)

## 🧼 Data Cleaning Steps
- Dropped rows with <1% missing (e.g., TAIL_NUMBER).
- No changes to conditionally missing delay values (cancellations/diversions).
- Imputed missing ELAPSED_TIME using: `ARRIVAL_TIME - DEPARTURE_TIME`.
- Skipped delay reason columns with 79–96% missing due to low analytical impact.

## 🔍 Key Analyses & Insights

### 1. 🕓 On-Time Performance by Airline
- **Top**: Delta (70.12%), Alaska (68.21%), Southwest (62.44%)
- **Bottom**: Frontier (46.29%), Hawaiian (50.74%)

### 2. 📅 Delays/Cancellations by Day of Week
- **Most Cancellations**: Monday (5.41%)
- **Most Delays**: Friday (41.62%)
- **Least Issues**: Saturday

### 3. 🌐 Most Connected Airports
- ATL (Atlanta): 241 destinations  
- ORD (Chicago O'Hare): 203  
- DFW (Dallas/Fort Worth): 167  

### 4. ⏱️ Scheduled vs Actual Duration
- **Most Deviation**: United (13.75 mins), Delta (12.6)
- **Least Deviation**: Hawaiian (6.52 mins)

### 5. 🛫 Fleet Utilization (Flights per Aircraft)
- **Highest**: Southwest (14,787), Delta (9,619)
- **Lowest**: Virgin America (641)

### 6. 🌦️ Delay Correlation with Geography & Season
- **Worst Performer**: Delaware (78 min dep. delay in Feb)
- **Winter Impact**: MA, NY, NE show spikes in delays during February.

## 🛠 Tools Used
- Microsoft Excel
- Charts, PivotTables, Conditional Formatting
- Basic Excel formulas (IF, AVERAGEIFS, VLOOKUP)

## 📌 Conclusion
This project reveals how operational, seasonal, and geographic factors impact flight punctuality. Excel proves powerful for data-driven insights even on large transportation datasets.

---

