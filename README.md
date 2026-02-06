# Online Course User Behavior Analysis

## 📌 Project Description
This project aims to analyze user behavior and engagement in online courses using data analysis techniques.
By exploring user activity, performance, and completion patterns, the project helps in understanding how learners interact with online educational platforms.

The analysis focuses on identifying trends, detecting anomalies, and extracting insights that can support data-driven decisions in online learning environments.

---

## 📂 Dataset Overview
The dataset represents user interaction data collected from an online course platform and includes the following features:

- **UserID**: Unique identifier for each user
- **CourseCategory**: Category of the enrolled course
- **TimeSpentOnCourse**: Total time spent by the user on the course
- **NumberOfVideosWatched**: Number of videos watched by the user
- **NumberOfQuizzesTaken**: Total quizzes attempted by the user
- **QuizScores**: Average quiz score per user
- **CompletionRate**: Course completion percentage
- **DeviceType**: Device used to access the course

---

## 🛠 Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning & Preprocessing
Several preprocessing steps were applied to ensure data quality and consistency:

- Handling missing values:
  - Numerical features were filled using the **median** to reduce the impact of outliers
  - Categorical features were filled using the **mode**
- Outlier detection and removal:
  - Extreme values were identified and removed using the **Interquartile Range (IQR)** method
- Data validation:
  - Verified that the dataset contains **no missing values** after cleaning

---

## 📊 Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to understand the data distribution and relationships between features:

- Distribution analysis using histograms and boxplots
- Correlation analysis between numerical features
- Visualization of engagement metrics across different course categories
- Detection of behavioral patterns affecting course completion

---

## 🔍 Feature Engineering & Dimensionality Reduction
To improve data interpretability and reduce complexity:

- Feature scaling was applied to numerical variables
- **PCA (Principal Component Analysis)** was used to reduce dimensionality
- Visualized principal components to observe clustering and variance distribution

---

## 📈 Visualization Techniques
The project includes multiple visualization techniques such as:
- Histograms and boxplots
- Correlation heatmaps
- Scatter plots for PCA components
- Filtered visualizations to highlight key patterns

---

## 🎯 Key Insights & Findings
- User engagement varies significantly across different course categories
- Higher time spent on courses generally leads to better completion rates
- Quiz participation has a strong relationship with user performance
- PCA successfully reduced dimensionality while preserving important patterns in the data

---

## 🚀 How to Run the Project
1. Open the notebook using **Google Colab** 
2. Ensure the required libraries are installed
3. Run all cells sequentially to reproduce the analysis and visualizations

---

## 📌 Future Improvements
- Apply machine learning models for performance prediction
- Add clustering techniques to segment users
- Enhance visual interactivity
- Integrate additional behavioral features

---

## 📝 Conclusion
This project demonstrates a complete data analysis workflow, starting from data cleaning and preprocessing to visualization and dimensionality reduction.
It provides meaningful insights into online course user behavior and highlights the importance of data-driven analysis in educational platforms.
