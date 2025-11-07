# 📊 E-commerce Data Analysis using Python (EDA)

## 🧠 Overview
This project performs *Exploratory Data Analysis (EDA)* on an E-commerce dataset to understand customer behavior, product performance, and overall sales trends.  
The analysis uses *Python* libraries — Pandas, Matplotlib, and Seaborn — to clean, explore, and visualize the data.

---

## 🧰 Tools & Libraries Used
- Python (Anaconda / Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn

---

## 📁 Dataset Information
*Dataset Name:* E-commerce Dataset.csv  
*Rows:* 119  
*Columns:* 15  

*Features include:*
- customer_id, first_name, last_name, gender, country
- product_id, product_name, category
- quantity, unit_price, rating, payment_method, order_status
- review_text

*New column created:*
- total_amount = quantity × unit_price

---

## 📈 Analyses Performed
1. Checked dataset structure using .info() and .describe()
2. Analyzed categorical columns using .value_counts()
3. Handled missing and duplicate values
4. Created total_amount column for each order
5. Visualized insights using:
   - *Histogram* → Distribution of numeric columns
   - *Boxplot* → Detecting outliers
   - *Countplot* → Category and payment method distribution
   - *Barplot* → Average rating per category
   - *Heatmap* → Correlation between numeric variables
   - *Pairplot* → Relationship visualization

---

## 🔍 Key Insights
- Dataset is clean with *no missing or duplicate values*.  
- *Top categories:* Apparel and Electronics.  
- *Most common payment method:* Cash on Delivery.  
- *Ratings:* Mostly between 2 and 5, with an average of around 3.  
- *High correlation* found between quantity, unit_price, and total_amount.  
- A few *outliers* represent bulk or high-value purchases.  

---

## 📄 Deliverables
| File | Description |
|------|--------------|
| EDA_Ecommerce.ipynb | Jupyter Notebook containing all code, visuals, and observations |
| EDA_Report.pdf | Final summary report exported from the notebook |
| E-commerce Dataset.csv | Source dataset used for analysis |

---

## 🧠 Conclusion
This project demonstrates how to perform data cleaning, exploration, and visualization using Python.  
It helped extract valuable insights about customer purchase patterns and product performance, improving decision-making potential for business strategy.

---

## 👤 Author
*Somasekhar Kadiyam*  
📧 sekhar.kadiyam002@gmail.com 
💼 [LinkedIn Profile ](https://www.linkedin.com/in/soma-sekhar-kadiyam-842707321)

---

⭐ If you found this project helpful, don’t forget to give it a star on GitHub!
