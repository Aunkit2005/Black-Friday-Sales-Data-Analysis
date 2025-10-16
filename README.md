# 🛍️ Black Friday Sales Data Analysis  

## 📖 Overview
**Black Friday** is one of the most popular shopping events, known for its massive discounts and record-breaking sales.  
This project explores the **Black Friday Sales Dataset** to uncover insights about customer purchasing behavior across various demographics such as **age, gender, occupation, and marital status**.  

Through this project, we analyze individual factors, combine multiple columns, and visualize data to reveal patterns that help understand consumer trends during Black Friday.  

---

## 🎯 Project Objectives
- Perform **Exploratory Data Analysis (EDA)** on the Black Friday dataset  
- Understand **customer demographics** and **purchasing trends**  
- Analyze how **gender, age, occupation, and marital status** influence spending behavior  
- Combine multiple factors to uncover **deeper insights** into consumer habits  

---

## 🧰 Prerequisites
Before running this project, make sure you are familiar with:  
- **Python** (Basic programming)  
- **Pandas** (Data manipulation and analysis)  
- **Matplotlib & Seaborn** (Data visualization)  
- **Jupyter Notebook** (Interactive environment for analysis)  
- Basic data cleaning and handling missing values  

---

## 📊 Dataset Details
| Feature | Description |
|----------|-------------|
| **Dataset Name** | Black Friday Sales Data |
| **File Size** | 23 MB (CSV) |
| **Rows** | ~537,000 |
| **Columns** | 12 |
| **Source** | [Black Friday Sales Dataset](#) *(Insert actual dataset link)* |

### 🧾 Column Information
- **User_ID** – Unique ID of the customer  
- **Product_ID** – Unique ID of the product purchased  
- **Gender** – Male or Female  
- **Age** – Age group of the customer  
- **Occupation** – Type of occupation (coded)  
- **City_Category** – Category of the city (A, B, or C)  
- **Stay_In_Current_City_Years** – Duration of stay in the current city  
- **Marital_Status** – 0 (Single) or 1 (Married)  
- **Product_Category_1, 2, 3** – Product categories purchased  
- **Purchase** – Purchase amount  

---

## 🧩 Project Steps

### 1️⃣ Walkthrough of the Dataset
- Loaded the dataset into a pandas DataFrame  
- Inspected structure using `df.info()` and `df.describe()`  
- Checked for missing values and inconsistencies  



---

### 2️⃣ Analyzing Columns
- Explored individual columns like **Gender**, **Age**, **Marital_Status**, and **Product_Category**  
- Handled missing data by dropping sparse columns (`Product_Category_2`, `Product_Category_3`)  
- Used `unique()` and `nunique()` to understand categorical distributions  



---

### 3️⃣ Gender Analysis
- Found **more male customers** than female customers in the dataset  
- Using `groupby()`, analyzed total purchases by gender  
- Visualized purchase trends with bar and pie charts  


---

### 4️⃣ Age & Marital Status Analysis
- Compared purchase patterns across **age groups** and **marital statuses**  
- Identified which age groups and marital categories spent the most  
- Created visualizations using Matplotlib and Seaborn  



---

### 5️⃣ Multi-Column Analysis
- Combined **Age**, **Gender**, and **Marital Status** to uncover deeper insights  
- Used `groupby()` and visualizations (bar charts, pie charts)  
- Analyzed how combined factors affect purchasing behavior  



---

### 6️⃣ Occupation & Products Analysis
- Explored how **occupation** influences **product preferences**  
- Examined **Product_Category_1** and **Product_ID** with respect to occupation  
- Identified most popular product categories for each occupation  



---

### 7️⃣ Combining Gender & Marital Status
- Studied the interaction between **Gender** and **Marital Status**  
- Used Seaborn’s `countplot()` to visualize combined purchasing patterns  
- Revealed differences in spending habits among married/unmarried men and women  



---

## 📈 Tools & Libraries Used
- **Python** 🐍  
- **Pandas** – Data cleaning and manipulation  
- **Matplotlib** – Data visualization  
- **Seaborn** – Advanced statistical plots  
- **Jupyter Notebook** – Interactive analysis  

---

## 🧠 Key Insights
- Majority of customers were **male** and made higher purchases.  
- **Young adults (26–35)** were the most active spenders.  
- **Married individuals** tend to spend more than singles.  
- Certain **occupations** showed higher purchasing power for specific product categories.  
- Combining demographics revealed strong correlations between **gender, age, and spending habits**.

---

## ✅ Conclusion
This project demonstrates how data analysis can be used to uncover hidden patterns in customer behavior.  
By exploring demographic and product-based data, we can derive actionable insights that can help retailers plan better marketing strategies and product placements for future Black Friday events.  


