# Employee-Salary-Prediction

Welcome to my Employee Salary Prediction repository! This project focuses on building a machine learning model to predict employee salaries based on features such as experience, test scores, and interview scores.
 
### 🚀 Project Overview

In this project, I worked with a hiring dataset containing both numerical and text-based data, along with missing values. The goal was to clean the data, handle text-to-number conversions, address missing data robustly, and train a predictive model.

### 🧠 Key Learnings & Takeaways

Working through this project helped me master several crucial data preprocessing techniques:

#### 1) Text-to-Integer Conversion for Word Numbers:

Learned how to handle categorical text data where numbers are written out as words (e.g., "five", "two", "eleven") and map/convert them into their proper integer format (5, 2, 11) for machine learning compatibility.

#### 2) Handling Missing Values Using the Median:

Imputed missing values in numerical columns by replacing them with the median rather than the mean.

### 3) Why Median Over Mean?

Discovered that the median is a much more robust measure of central tendency than the mean when dealing with skewed data or outliers. Because the mean is heavily affected by extreme values (outliers), using the median provides a safer, more representative estimate for filling missing values.

📁 ## Repository Structure

Employee_Salary_Prediction.ipynb: The Jupyter Notebook containing the data preprocessing, exploratory data analysis, and model training code.

hiring_data.csv: The dataset used for training and testing the model.
