# 🏥 Health Insurance Risk & Cost Driver Analysis

## 📌 Project Overview
This project analyzes a dataset of 1,338 insured individuals to identify the primary drivers of medical insurance costs. As a Business Intelligence (BI) exercise, the goal is to provide actionable insights for insurance underwriting teams to refine pricing strategies and identify high-risk populations.

## 🚀 Key Business Insights
* **Lifestyle Impact:** Smoking is the #1 cost driver, adding an average of **$23,651** to annual charges.
* **Risk Intersection:** The combination of **Obesity (BMI > 30)** and **Smoking** creates a "cost cliff," significantly increasing financial liability compared to lean smokers.
* **Geographic Trends:** The **Southeast US** is the most expensive region, directly correlating with higher regional BMI and smoking prevalence.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `Pandas`: Data manipulation and cleaning
    * `Seaborn` & `Matplotlib`: Advanced data visualization (Violin plots, Donut charts, Heatmaps)

## 📂 Project Structure
1. **Descriptive Profiling:** Segmenting the population by Age, Region, and BMI.
2. **Cost Driver Analysis:** Quantifying the correlation between lifestyle and charges.
3. **Actuarial Trends:** Mapping the cost of aging across different segments.
4. **Regional Performance:** Identifying geographic risk outliers.
5. **Predictive Modeling:** Building a "What-If" calculator for charge estimation.

## 📈 Visualizations Highlights
The project utilizes professional-grade visuals including:
* **Donut Charts** for health composition.
* **Violin Plots** for distribution analysis.
* **Regression Plots** for actuarial aging curves.
* **Heatmaps** for feature correlation.

## 📋 How to Run
1. Clone the repository.
2. Ensure you have `requirements.txt` dependencies installed:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
