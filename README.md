# Student Performance Analysis - EDA Project

This project analyzes a dataset of student performance across various subjects. It includes data cleaning, normalization, outlier removal, and visual exploration using Python Libraries (Pandas, Matplotlib, Seaborn).

---

## Dataset

The dataset includes:
- Math score
- Reading score
- Writing score
- Gender
- Race/ethnicity
- Parental level of education
- Lunch
- Test preparation course

---

## Project Steps

1. **Loading the dataset**
2. **Handling missing values** (dropped unnecessary column)
3. **Standardization of numerical features**
4. **Outlier Detection** using:
   - IQR method
   - Z-score method
5. **Exploratory Data Analysis**:
   - Histograms
   - Boxplots
   - Scatterplots
   - Heatmaps
6. **Statistical summaries** (mean, median, std)
7. **Interesting Insights**:
   - Correlation between subjects
   - Clusters of high/low performers
   - Detected anomalies (outliers)

---

## 📊 Visuals

- **Scatter plots** to observe relationships
- **Box plots** to detect outliers
- **Heatmap** to check feature correlations
- **Pairplot** for cluster visualization

---

## Files

| File                                 | Description                                     |
|--------------------------------------|-------------------------------------------------|
| `student_performance_analysis.ipynb` | Jupyter notebook with full analysis             |
| `requirements.txt`                   | List of required Python libraries               |


---

## Technologies Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy

---

## Clone Repository

```bash
git clone https://github.com/Khansa05/student-performance-eda.git
cd student-performance-eda
pip install -r requirements.txt
