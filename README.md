
# 🏡 USA Housing Data Science Project

This project explores the USA Housing dataset using Python libraries such as pandas, matplotlib, and seaborn. The primary objective is to identify which features have the greatest influence on housing prices through exploratory data analysis (EDA) and visualization.

---

## 📊 Dataset Overview

The dataset (`USA_Housing.csv`) contains the following features:

- `Avg. Area Income`: Average income of residents in the area
- `Avg. Area House Age`: Average age of houses in the area
- `Avg. Area Number of Rooms`: Average number of rooms per house
- `Avg. Area Number of Bedrooms`: Average number of bedrooms per house
- `Area Population`: Population of the area
- `Price`: Target variable (house price)
- `Address`: Text field (not used in correlation analysis)

---

## 🔍 Project Workflow

1. **Data Loading**  
   Loaded the CSV and verified structure using `head()`, `info()`, and `describe()`.

2. **Data Cleaning & Validation**  
   - Checked for missing values (none found).
   - Validated column types.

3. **Exploratory Data Analysis (EDA)**  
   - Plotted histograms and boxplots for all numerical features.
   - Scatter plots between each feature and housing price to understand relationships.
   - Generated a correlation heatmap to identify strong predictors of price.

4. **Address Column Analysis**  
   - Found 5000 unique values.
   - Could be used for feature engineering in future modeling (e.g., extracting city or zip code).

5. **Reporting**  
   - Summarized findings and saved as `data_exploration_report.txt`.

---

## 🖼️ Visual Examples

*Visualizations were generated for:*
- Distribution of each numerical feature
- Boxplots for outlier detection
- Scatter plots vs. Price
- Correlation heatmap

---

## 📁 Repository Structure

```
USA-Housing-Analysis/
│
├── USA_Housing.csv                     # Dataset
├── USA_Housing_Case_Study.ipynb       # Main Jupyter Notebook
├── data_exploration_report.txt        # Written summary of insights
├── README.md                          # This file
```

---

## 🚀 Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 💡 Key Insights

- **Avg. Area Income**, **Avg. Area Number of Rooms**, and **Area Population** had the highest correlation with **Price**.
- The **Address** column, while unique for each row, can be parsed for geographical insights in future work.

---

## 🔮 Future Work

- Build regression models (Linear, Ridge, etc.) to predict price.
- Feature engineering from the `Address` column.
- Deploy a visualization app (e.g., using Streamlit or Flask).

---

Made with ❤️ by [Yash Hooda](https://github.com/yashhooda1)
