# 🫀 US Cardio Data Analysis  

## 📌 Overview  
This project analyzes **cardiovascular health data** to explore patterns in **age, cholesterol levels, smoking habits, blood pressure, and other health indicators**. The analysis was conducted using **Python (Pandas, NumPy, Matplotlib, SciPy)** and aims to answer key research questions related to heart health trends.  

## 📂 Repository Structure  
```
📁 cardio-data-analysis  
 ├── 📄 cardio_data_analysis.ipynb  # Jupyter Notebook with full analysis  
 ├── 📄 cardio_data_analysis.pdf    # PDF version of the notebook  
 ├── 📊 data/                       # Folder containing dataset(s)  
 │    ├── cardio_base.csv           # Main dataset  
 │    ├── cardio_alco.csv           # Additional dataset (alcohol consumption)  
 │    ├── covid_data.csv            # COVID-19 dataset used for external analysis  
 ├── 📄 README.md                   # Project documentation  
```

## 🔬 Key Analysis Questions & Insights  

1️⃣ **Do older individuals (50+ years) have higher cholesterol levels?**  
   - ✅ Yes, **cholesterol levels are higher for individuals over 50** compared to younger individuals.  

2️⃣ **Which age group has the highest and lowest average weight?**  
   - ✅ **Highest:** **63 years**  
   - ✅ **Lowest:** **30 years**  
   - ✅ **Weight difference:** **16.87 kg** (~28.6% difference)  

3️⃣ **Are men more likely to smoke than women?**  
   - ❌ **No. Women are more likely to smoke than men** based on dataset analysis.  
   - **Smoking rate:** **Men: 1.79%** | **Women: 21.89%**  

4️⃣ **What is the height of the tallest 1% of individuals?**  
   - ✅ **184.00 cm**  

5️⃣ **Which two features have the highest Spearman correlation?**  
   - ✅ **Systolic (ap_hi) & Diastolic Blood Pressure (ap_lo)** (Correlation: **0.74**)  

6️⃣ **What percentage of people have extreme height values (±2 std deviations)?**  
   - ✅ **3.34% of the population**  

7️⃣ **What percentage of people over 50 consume alcohol?**  
   - ✅ **5.34%** (Merged `cardio_base.csv` & `cardio_alco.csv` datasets)  

8️⃣ **Statistical Confidence Testing (95%)**  
   - ✅ **Smokers have higher cholesterol levels than non-smokers**  
   - ✅ **Smokers weigh less than non-smokers**  
   - ❌ **Men do not have higher blood pressure than women**  
   - ❌ **Smokers do not have higher blood pressure than non-smokers**  

## 📊 COVID-19 External Analysis  
- **When did the difference in confirmed cases between Italy & Germany exceed 10,000?**  
  - ✅ **March 12, 2020**  
- **Exponential Modeling of Italy’s Cases (Feb 28 – Mar 20, 2020)**  
  - ✅ **Predicted cases on March 20, 2020: 42,346**  
  - ✅ **Actual cases: 40,635**  
  - ✅ **Difference: 1,711 cases**  

## ⚡ Technologies Used  
- **Python** (Pandas, NumPy, Matplotlib, SciPy)  
- **Jupyter Notebook**  
- **Statistical Analysis (Spearman Correlation, T-tests)**  

## 📌 How to Use  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/cardio-data-analysis.git
   cd cardio-data-analysis
   ```
2. **Install dependencies**  
   ```bash
   pip install pandas numpy matplotlib scipy
   ```
3. **Open the Jupyter Notebook**  
   ```bash
   jupyter notebook cardio_data_analysis.ipynb
   ```

## 📢 Key Takeaways  
✅ **Older individuals have higher cholesterol**  
✅ **Women smoke more than men in this dataset**  
✅ **Systolic & Diastolic Blood Pressure are strongly correlated**  
✅ **COVID-19 cases in Italy followed an exponential pattern**  

---

📧 **For inquiries or collaborations, contact:** johmusyomi@gmail.com  

🚀 **Happy Analyzing!**  
```
