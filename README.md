# 🦟 Malaria Mosquito Database (1898–2016)

This project analyzes over a century’s worth of mosquito vector data across Africa, with a focus on *Anopheles* species—key vectors for malaria. It aims to identify geographic, temporal, and environmental patterns, and apply machine learning to aid global health strategies for malaria control.

---

## 🚀 Objectives

- Understand the distribution of *Anopheles* mosquito species across Africa.
- Reveal long-term sampling trends (1898–2016).
- Visualize geospatial spread using interactive maps.
- Predict mosquito presence using machine learning.
- Identify high-impact zones for health intervention and funding prioritization.

---

## 🧪 Tools & Libraries

- **Data Analysis**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`, `folium`
- **Machine Learning**: `scikit-learn` (Random Forest Classifier, Permutation Importance)
- **Geospatial Mapping**: `folium`, `MarkerCluster`, `HeatMap`

---

## 📊 Project Overview

### 1. Data Exploration

- Displays dataset structure: column names, types, and missing values.
- Summarizes statistical distribution of values.
- Identifies key columns with missing data.

### 2. Top Species Visualization

- Horizontal bar chart of the most frequently observed *Anopheles* species.
- Highlights **An. gambiae** as the most common malaria vector.

### 3. Temporal Sampling Trends

- Line graph illustrating sampling frequency from **1898 to 2016**.
- Peak sampling activity occurs in the 2000s.

### 4. Geospatial Visualization

- Interactive **Folium map** showing sample locations across Africa.
- Color-coded markers representing vector species and countries.

---

## 🤖 Machine Learning Models

### 🔬 Example 1: Predicting *An. gambiae* Presence

- **Model**: Random Forest Classifier
- **Top Predictors**:
  - Latitude
  - Longitude
  - Year of sampling
- **Visualizations**:
  - ROC curve
  - Confusion matrix
  - Feature importance plots

### 🧭 Example 2: WHO Intervention Decision Model

- Predicts **WHO malaria control intervention priorities**.
- Analyzes feature importance for strategic planning.
- Generates a **country-level heat map** of priority scores.
- Recommends high-impact countries (e.g., **Guinea Bissau**, **Equatorial Guinea**) for urgent intervention.

---

## 📌 Key Insights

- **An. gambiae** is the most sampled and significant vector.
- **Temporal trends** suggest increased surveillance from 2000 onward.
- **Geospatial coverage** is uneven; West & Central Africa are well-represented.
- **Predictive power** is strongest for geographic and temporal features.
- **Data-driven models** can inform national and global intervention strategies.

---

## 📢 Recommendations

- Increase sampling in **underrepresented regions**.
- Prioritize **recent data collection** for timely decision-making.
- Use **geographic and temporal trends** to guide WHO resource allocations.
- Integrate **vector mapping** into national malaria control strategies.

---

## 📂 Dataset Source

**Africa Vector Database (1898–2016)**  
Includes mosquito species data, geolocation, year of sampling, and associated metadata.

---

## 💡 Conclusion

This project demonstrates the power of **data science** and **machine learning** in shaping public health strategies. With targeted interventions based on real-time analysis, health organizations can **maximize the impact** of limited resources in the fight against malaria.
