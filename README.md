# 🚨 911 Calls Data Analysis - Montgomery County, PA

## 📌 Project Overview
This project analyzes 911 emergency call data from Montgomery County, Pennsylvania. The 911 system is a critical public safety feature in the USA, serving as the primary emergency contact number for citizens reporting crimes, medical emergencies, traffic incidents, fires, and more. 

As a Data Analyst on this project, the goal is to perform data manipulation, feature engineering, and exploratory data analysis (EDA) to extract meaningful insights and visualize emergency response trends.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

## 📋 Analysis Tasks & Key Questions

This project is broken down into several computational tasks, each designed to answer specific questions about the dataset.

### 1. Zipcode Analysis
* **Compute:** Identify the top 10 zipcodes for 911 calls.
* **Question 1:** Are Zipcodes `19446` and `19090` present in the top 10 list?
  * *Answer:* [Insert your answer here]

### 2. Township Analysis
* **Compute:** Identify the top 4 townships (`twp`) for 911 calls.
* **Question 2:** Which of the following townships are *not* present in the top 4? (LOWER POTTSGROVE, NORRISTOWN, HORSHAM, ABINGTON)
  * *Answer:* [Insert your answer here]

### 3. Feature Engineering: Call Reasons
* **Compute:** Create new features based on the existing data (e.g., extracting the specific Reason/Department from the Title column).
* **Question 3:** What is the most common reason for a 911 call based on the new Reason column? Which reason comes in second?
  * *Answer:* [Insert your answer here]

### 4. Data Visualization: Calls by Reason
* **Compute:** Plot a bar chart using Matplotlib/Seaborn to display the total number of 911 calls for each Reason.
* **Question 4:** How can you plot these bars horizontally using Matplotlib/Seaborn?
  * *Answer:* [Explain the function/parameter used, e.g., using `plt.barh()` or setting `y='Reason'` in Seaborn]

### 5. Data Manipulation: EMS Calls by Day
* **Compute:** Perform data manipulation to group calls by Date/Day and Reason.
* **Question 5:** Which day received the maximum number of calls specifically for EMS, and exactly how many calls were there?
  * *Answer:* [Insert day and call count here]

### 6. Visualizing Weekly Trends
* **Compute:** Create a `countplot` of the *Day of Week* column, using the *Reason* column as the `hue`.
* **Question 6:** Based on the plot, on which day of the week were *Traffic* calls the lowest?
  * *Answer:* [Insert your answer here]

### 7. Visualizing Monthly Trends
* **Compute:** Create a `countplot` mapping the calls month-wise.
* **Question 7:** Which month saw the highest number of calls for *Fire* emergencies?
  * *Answer:* [Insert your answer here]

---**for answers check the project 

