# Statistical Analysis of Diabetes Prevalence

## 📌 Project Overview
This project explores the **prevalence of diabetes** using **statistical modeling and hypothesis testing** to analyze demographic and geographic factors. The study identifies **significant correlations** between diabetes diagnosis and factors such as **age, gender, and region**, using real-world datasets.

## 📊 Dataset & Analysis
The dataset consists of **demographic and health-related attributes** of individuals diagnosed with diabetes. The key objectives include:
- Understanding how **age and gender** influence diabetes prevalence.
- Investigating **regional and urban vs. rural** differences in diabetes distribution.
- Applying **statistical tests** to determine the significance of various factors.

## 🔬 Methodology
### 1️⃣ Data Preprocessing
- **Data Cleaning:** Handling missing values and normalizing attributes.
- **Data Transformation:** Converting categorical variables for statistical analysis.

### 2️⃣ Statistical Tests & Analysis
- **Chi-Square Test (χ²):** Evaluates independence between categorical variables.
- **T-Test (t-test_ind):** Compares mean glucose levels across different groups.
- **Descriptive Statistics:** Measures central tendency and variability.
- **Distribution Analysis:** Evaluates skewness and normality.

## 🚀 Key Findings
- **Age is a significant factor:** The **average age of individuals with diabetes** is **57.68 years**, compared to **41.09 years** for those without.
  - **T-Statistic:** 19.65, **p-value:** 5.24e-65 (**p < 0.05**, significant difference).
- **Gender influences diabetes prevalence:**
  - **Chi-Square Test:** χ² = 7.6581, **p-value:** 0.0056 (**p < 0.05**).
  - **Conclusion:** There is a **significant association** between gender and diabetes diagnosis.
- **No significant correlation** was found between **region** and diabetes presence (**p = 0.345**), nor between **urban vs. rural residency** (**p = 0.572**).

## 📂 Files in This Repository
- `finalAnalysis.ipynb` - Jupyter Notebook containing full data analysis, visualizations, and statistical tests.
- `distribucionDePersonasConDiagnosticoDeDiabetes.pdf` - Report summarizing findings and methodology.

## 🔧 Technologies Used
- **Python** (`pandas`, `numpy`, `scipy.stats`, `matplotlib`, `seaborn`)
- **Statistical Analysis** (T-Tests, Chi-Square Tests, Data Distributions)
- **Data Visualization** (Histograms, Box Plots, Heatmaps)

## 👨‍💻 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook finalAnalysis.ipynb
   ```

## 🏆 Project Impact
This project provides **statistical insights into diabetes prevalence**, helping to identify key risk factors and inform **public health strategies**.

## 📩 Contact
For inquiries, feel free to reach out via GitHub or email.
