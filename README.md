# Chicago Crime Analysis and Predictive Modeling

This analysis explores crime data from the City of Chicago, focusing on identifying crime trends, clustering high-crime areas, and building predictive models to assist policymakers and law enforcement in improving public safety. The analysis includes data cleaning, exploratory data analysis (EDA), advanced statistical modeling, and clustering techniques, with actionable insights for crime prevention strategies.

---

## **Project Overview**
The primary objectives of this project are to:
1. Understand spatial and temporal crime patterns in Chicago.
2. Identify high-risk areas using clustering techniques. **(WIP)**
3. Build predictive models for arrest likelihood and identify influential features. **(WIP)**
4. Provide actionable recommendations for policymakers and law enforcement.

The project uses Python and includes data processing, visualization, and advanced machine learning techniques.

---

## **Data Source**
The data for this project is sourced from the [City of Chicago's Crime Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data).  
- **Data Period**: January 19, 2021, to January 19, 2025.
- **Features**: Incident date, location, primary crime type, arrest status, and community area.

---

## **Project Structure**
The repository includes the following components:

### **1. Data Cleaning**
- Handled missing values and removed duplicates.
- Converted timestamps to meaningful features like `Month`, `Hour`, and `Weekday`.
- Filtered data for analysis, focusing on incidents from 2021 to 2025.

### **2. Exploratory Data Analysis (EDA)**
- Visualized crime counts by year, month, weekday, and hour.
- Analyzed crime types and their frequency.
- Assessed arrest rates and domestic crime proportions.
- Heatmaps to identify time-of-day and area-specific trends for theft and battery incidents.

### **3. Advanced Statistical Modeling** (WIP)
- Built machine learning models (Logistic Regression, Random Forest, and XGBoost) to predict arrest likelihood.
- Evaluated models using accuracy, ROC AUC, and classification reports.
- Identified important features affecting arrests using feature importance visualizations.

### **4. Clustering**
- Applied K-Means clustering to identify high-crime hotspots.
- Validated clusters and analyzed crime types, times, and locations within each cluster.

### **5. Recommendations**
- Provided data-driven recommendations for resource allocation, policy adjustments, and intervention strategies.

---

## **Key Findings**
### **Spatial and Temporal Patterns**
- Crime hotspots identified in areas with high theft and battery incidents.
- Crime peaks during summer months and midday hours, with noticeable late-night spikes.

### **Crime Type Insights**
- Theft and battery are the most frequent crimes, with theft accounting for 23% of all crimes.
- Weapons violations have the highest arrest rates, while theft has the lowest.

### **Statistical Modeling**
- XGBoost achieved the best performance with:
  - **Accuracy**: WIP
  - **ROC AUC**: WIP
- Arrest prediction struggles with **class imbalance**, requiring further work.

---

## **Requirements**
### **Languages and Libraries**
- **Languages**: Python
- **Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for visualization.
  - `scikit-learn` and `xgboost` for modeling.
