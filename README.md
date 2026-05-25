# Developer Community & Compensation Analysis (Stack Overflow Survey)

This project focuses on evaluating the global software development market using the scale of the Stack Overflow Developer Survey dataset. It examines developer profiles, programming language penetration (specifically Python), remote work trends, and compensation benchmarks globally.

## 🛠️ Tech Stack & Environment
- **Language:** Python
- **Libraries:** Pandas, NumPy, SciPy (for descriptive statistics and data cleansing)
- **Environment:** Jupyter Notebook / Google Colab

## 📊 Analytical Tasks & Solutions Implemented
1. **Data Audit & Completeness:** Evaluated missing values (`NaN`) and structure variations using dataset schemas and mathematical set intersection methods to ensure data integrity.
2. **Experience Metrics:** Computed measures of central tendency (mean, median, mode) for continuous metrics like years of professional experience (`WorkExp`), effectively accounting for highly skewed distributions.
3. **Technology & Education Penetration:** Parsed multi-valued semi-structured text data fields to evaluate exact Python usage statistics and isolated the impact of modern alternative educational paths (such as online coding courses).
4. **Global Compensation Analysis:** Performed multi-dimensional geographical and categorical aggregations to evaluate median global compensation and isolate high-earning distributions using the 75th percentile across key regions.

## 🚀 Key Project Insights
- Evaluated the commercial viability of alternative educational paths, proving their cost-efficiency in modern developer onboarding.
- Formed clear analytical tables structuring global income distributions, outlining exact factors that drive maximum compensation metrics.
- Mapped remote work distribution percentages across target geographic tech hubs.

## 📁 How to View the Project
The entire exploratory data analysis (EDA), logic steps, Python code blocks, and resulting data tables are fully processed and rendered right inside the `stackoverflow_developer_analysis.ipynb` file in this repository. 

*(Note: If the `.ipynb` file displays a rendering error on mobile screens due to its size, please switch your mobile browser to **Desktop Site** mode or view it on a computer to see the fully rendered notebook).*