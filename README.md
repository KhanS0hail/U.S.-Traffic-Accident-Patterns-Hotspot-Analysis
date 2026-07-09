# U.S. Traffic Accident Patterns & Hotspot Analysis

A large-scale spatio-temporal and exploratory data analysis (EDA) project mapping nationwide traffic accident hotspots, tracking yearly trends, and identifying environmental risk factors.

## 📌 Project Overview
Traffic accidents represent a critical public safety and urban planning challenge. This project analyzes nationwide traffic accident records to identify hotspots and understand how external conditions—such as weather, time of day, and location factors—affect accident frequency and severity.

## 🚀 Key Features
* **Geospatial Hotspot Mapping:** Plots geographic coordinate distributions (Latitude/Longitude) to isolate high-risk zones across different states.
* **Environmental Impact Analysis:** Correlates accident frequencies with weather conditions (e.g., rain, snow, fog, clear skies).
* **Temporal Trend Analysis:** Compares historical accident data across different years and months to detect trends.
* **Severity Profiling:** Breaks down accident severity levels and details how environmental factors correlate with higher-severity events.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing & Manipulation:** Pandas, NumPy
* **Data Visualization & GIS Plotting:** Matplotlib, Seaborn

## 📈 Methodology & Pipeline
1. **Data Acquisition:** Sourced nationwide traffic event records from the [Kaggle US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents).
2. **Data Cleaning & Wrangling:**
   * Parsed timestamps into distinct Year, Month, Day, and Hour fields.
   * Handled missing spatial data and filtered outliers to ensure geographical plotting accuracy.
3. **Exploratory Data Analysis (EDA):**
   * Ranked states and cities by total accident volume to locate high-density zones.
   * Analyzed accident distributions across categorical parameters (Weather, Severity).
4. **Data Visualization:**
   * Created spatial scatter plots based on geographical coordinates.
   * Constructed severity pie charts, environmental factor histograms, and state-by-state comparisons.

## 💡 Key Insights
* **Geographic Clusters:** Major metropolitan zones like Miami and high-density states like California reported the highest accident volumes, corresponding to high traffic concentration.
* **Environmental Findings:** Interestingly, the majority of recorded accidents occurred during **fair weather** conditions. This suggests that human error, high traffic density, or driver distraction might play a more significant role in accident occurrences than poor weather conditions.
* **Severity Distribution:** Most accidents were classified as Severity Level 2 (moderate impact/delays), indicating that while traffic accidents are frequent, severe/catastrophic crashes represent a smaller fraction of the dataset.

## 📂 Project Structure
```text
├── us_traffic_accident_analysis.ipynb # Spatial-temporal analytics and plotting notebook
└── README.md                          # Project documentation
```

## 👤 Author
* **Khan Sohail**
  * [LinkedIn](https://www.linkedin.com/in/khan-sohail-386b2027a)
  * Email: ks646397@gmail.com