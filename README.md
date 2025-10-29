**Coffee Dataset Analysis**

Comprehensive Exploratory Data Analysis (EDA) \& Data Cleaning Project



This project performs end-to-end data analysis on a coffee dataset — including data inspection, cleaning, transformation, visualization, and insights. It follows a structured data science workflow from raw data to meaningful business insights.



**Project Overview**



The goal of this project is to understand consumer coffee purchasing patterns by exploring, cleaning, transforming, and visualizing the dataset.



**Key Objectives:**



Identify missing, duplicate, or inconsistent data



Perform descriptive \& inferential statistics



Detect and treat outliers



Visualize univariate, bivariate, and multivariate relationships



Draw actionable insights for business decision-making



📁 **Dataset Details**



File: coffee.csv

Source: Internal / Custom Dataset



Dataset Summary



Rows: N (automatically determined)



Columns: M (automatically determined)



Data types: Numerical + Categorical



Target features: money\_spent, weekday, hour



**Project Workflow**

1\. Dataset Overview



Displayed first and last few rows (head(), tail())



Checked dataset shape (rows × columns)



Listed column names \& data types



Counted missing and unique values



2\. Data Quality Checks



Identified missing values



Detected duplicate records



Found incorrect values (e.g., negative amounts)



Fixed formatting issues (spaces, capitalization inconsistencies)



3\. Data Cleaning



Handled missing values (mean/median/mode imputation)



Removed duplicates



Corrected invalid entries



Standardized text formatting



4\. Descriptive Statistics



Calculated Mean, Median, Mode, Variance, Std. Deviation



Checked distribution (Skewness, Kurtosis)



Found value counts for categorical features



5\. Data Transformation \& Encoding



Scaled numerical columns using StandardScaler / MinMaxScaler



Encoded categorical features (Label Encoding \& One-Hot Encoding)



6\. Outlier Detection \& Treatment



Applied IQR and Z-Score methods



Visualized outliers using Boxplots



Treated outliers by capping or transformation



7\. Data Visualization

🔹 Univariate Analysis



Histogram \& Boxplots (Numerical)



Barplots (Categorical)



Distribution Plots (Seaborn)



🔹 Bivariate Analysis



Scatter Plots



Pair Plots



Correlation Heatmap



Grouped Bar/Line Charts



🔹 Multivariate Analysis



PCA (Principal Component Analysis) for dimensionality reduction



Stacked Bar Charts showing money\_spent by weekday and hour



📈 Key Insights



Spending Patterns: Customers spend the most on specific weekdays and time slots.



Feature Relationships: Strong correlation found between money\_spent, hour, and weekday.



Outliers: A few high-spend outliers identified and capped.



PCA Results:



PC1 = 30.2% variance



PC2 = 26.1% variance



Total Variance Captured = 56.3%



🛠️ Tech Stack

Category	Tools / Libraries

Language	Python

Data Handling	Pandas, NumPy

Visualization	Matplotlib, Seaborn

Statistics \& Transformation	SciPy, Scikit-learn

EDA Notebook	Jupyter Notebook / VS Code

📊 Visualizations Included



Histograms



Boxplots



Bar Charts



Scatterplots



Pairplots



Heatmaps



PCA 2D Projection



Stacked Bar Charts



🚀 How to Run



Clone the repository



git clone https://github.com/<your-username>/coffee-dataset-analysis.git

cd coffee-dataset-analysis





Install dependencies



pip install -r requirements.txt





Run the notebook or Python file



jupyter notebook coffee\_analysis.ipynb





or



python coffee\_analysis.py



📚 Future Improvements



Build interactive dashboards (Plotly / Streamlit)



Apply predictive models for coffee purchase forecasting



Deploy the analysis via Flask or FastAPI



Author



Gaurav Kumar

🎓 MSc Computer Science, MIT ACSC (SPPU)

