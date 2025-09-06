# wine_quality_analysis_using_central_tendency

# 🍷 Wine Quality Analysis using Central Tendency  

## 🔍 Project Overview  
This project analyzes the **Wine Quality dataset** to study the characteristics of its chemical features through the lens of **measures of central tendency**.  
Central tendency statistics such as **mean, median, and mode** are applied to summarize data, identify typical values, and understand the distribution of variables.  

By comparing these measures, the analysis reveals whether distributions are **normal (symmetric)** or **skewed**, which helps in identifying outliers and understanding the data more effectively.  

---

## 📊 Steps of Analysis  

### **1. Data Loading and Exploration**  
- Loaded the dataset using **Pandas**.  
- Studied dataset structure: number of rows, columns, data types, and feature names.  
- Key features include:  
  - Fixed acidity  
  - Volatile acidity  
  - Citric acid  
  - Residual sugar  
  - Chlorides  
  - Free sulfur dioxide  
  - Total sulfur dioxide  
  - Density  
  - pH  
  - Sulphates  
  - Alcohol  
  - Quality  

---

### **2. Central Tendency Analysis**  
For each feature, the following measures were calculated and compared:  

- **Mean** → Represents the average concentration of the chemical feature.  
- **Median** → Represents the middle value and shows robustness against outliers.  
- **Mode** → Represents the most frequent value.  

Comparison of these measures allowed us to check whether distributions were **symmetric (mean ≈ median ≈ mode)** or **skewed**.  

---

### **3. Visual Distribution Study**  
- Created **histograms** and distribution plots to understand feature distributions.  
- Examples of findings:  
  - *Fixed acidity* → Nearly normal distribution, mean and median close to each other.  
  - *Residual sugar* and *Chlorides* → Positively skewed (longer right tail).  
- Central tendency values were compared with plots to visualize how they describe the dataset.  

---

### **4. Key Observations**  
- Features with **symmetric distributions** → Mean ≈ Median.  
- Features with **skewed distributions** → Mean shifted in the skew’s direction, while Median stayed closer to the central point.  
- Mode was less informative for continuous variables but useful for detecting peaks.  
- Overall, the analysis highlighted which wine features are normally distributed and which are skewed — an important insight for further modeling.  

---

## 🛠️ Tools and Libraries  
- **Python** – Programming language  
- **Jupyter Notebook** – Interactive environment  
- **Pandas** – Data handling & exploration  
- **NumPy** – Numerical computations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical visualization  

---

## 📌 Conclusion  
This project serves as a **foundation for understanding wine quality data** using descriptive statistics.  
By studying central tendency measures, we gain insight into the nature of the dataset, which is crucial for deeper analyses such as:  
- Hypothesis testing  
- Correlation analysis  
- Predictive modeling of wine quality  

---
