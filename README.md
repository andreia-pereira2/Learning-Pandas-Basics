# 📊 Pandas Basics - Exploring Student Dataset

## 📌 Project Overview
This project focuses on learning and applying **Pandas**, one of the most powerful Python libraries for data manipulation and analysis. Using **Google Colab**, I worked with the **students.csv** file to explore and analyze the dataset effectively.

## 🔎 What is Pandas?
Pandas is an open-source Python library that provides data structures and data analysis tools. It is widely used in data science for tasks such as **data cleaning, transformation, and analysis**. The core data structure in Pandas is the **DataFrame**, which allows for efficient handling of tabular data.

## 🚀 Key Learning Outcomes
Throughout this project, I learned how to:

### 🔹 Inspect and Explore the Dataset
- `df.head()` - View the first few rows of the dataset
- `df.tail()` - View the last few rows of the dataset
- `df.dtypes` - Check the data types of each column
- `df.duplicated().sum()` - Count the number of duplicate rows

### 🔹 Data Selection & Manipulation
- **Subsetting DataFrames** - Selecting specific rows and columns
- **Locating Data**
  - `.loc[]` - Accessing data using labels
  - `.iloc[]` - Accessing data using index positions
- **Filtering Data** - Applying conditions to extract relevant data

## 🖼️ Sample Queries and Results
Below are some of the key operations performed in this project:

### 1️⃣ Viewing the First Five Rows of the Dataset
```python
import pandas as pd

df = pd.read_csv('students.csv')
df.head()
```
📌 **Result:** Displays the first 5 rows of the dataset, allowing a quick preview of the data structure.

### 2️⃣ Checking for Duplicates
```python
df.duplicated().sum()
```
📌 **Result:** Returns the total count of duplicate rows in the dataset.

### 3️⃣ Selecting Specific Columns
```python
df[['Name', 'Age', 'Grade']]
```
📌 **Result:** Extracts only the columns **Name, Age, and Grade** from the dataset.

### 4️⃣ Filtering Students Above 18 Years Old
```python
df[df['Age'] > 18]
```
📌 **Result:** Returns all students whose age is greater than 18.

## 📊 Visuals
I have included images showcasing the **queries and their corresponding outputs** to better understand the operations performed. 

<img width="268" alt="Screenshot 2025-02-18 at 16 53 35" src="https://github.com/user-attachments/assets/3ecaafc9-3d1f-46b6-b1bb-02afe2ea06b4" />

<img width="270" alt="Screenshot 2025-02-18 at 16 54 42" src="https://github.com/user-attachments/assets/50e97ec7-5df2-4998-9a7b-99b0d1ddef9c" />

<img width="181" alt="Screenshot 2025-02-18 at 16 55 15" src="https://github.com/user-attachments/assets/ffe4813b-dd2b-4356-9cae-fb2d9cc102a9" />

<img width="374" alt="Screenshot 2025-02-18 at 16 56 11" src="https://github.com/user-attachments/assets/5bf25f3d-39fb-473f-bee6-69aec6b604c0" />

<img width="215" alt="Screenshot 2025-02-18 at 16 56 37" src="https://github.com/user-attachments/assets/9aed67a1-5298-4ac1-9226-76819247c1c7" />

## 🏁 Conclusion
This project was a great introduction to **Pandas** and its capabilities in data manipulation and analysis. Moving forward, I plan to explore **data visualization and more advanced data wrangling techniques**.

🔹 **Technologies Used:** Python, Pandas, Google Colab  
📂 **Dataset:** students.csv  
🚀 **Next Steps:** Data Visualization, Aggregation, and Advanced Filtering  

---

📝 Feel free to check out the code, suggest improvements, or reach out for discussions on data analysis! 😃
