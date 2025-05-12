# Task 1 - Retail Store Sales Analysis

## 📌 Project Overview
This project performs an in-depth analysis of retail store sales data using Python. It includes exploratory data analysis (EDA), customer behavior insights, time-series trends, and visualizations to uncover business insights. The analysis is done in a Jupyter Notebook (`RetailStoreSalesAnalysis.ipynb`).

## 📂 Dataset Description
The dataset contains transactional data from a retail store with the following key fields:
- `InvoiceNo`: Unique identifier for transactions
- `StockCode`: Product identifier
- `Description`: Product name
- `Quantity`: Number of units sold
- `InvoiceDate`: Timestamp of the transaction
- `UnitPrice`: Price per unit
- `Customer ID`: Unique customer identifier
- `Country`: Country where the purchase was made
- `TotalRevenue`: Derived field (`Quantity * UnitPrice`)

Download the dataset from https://www.kaggle.com/datasets/harshwalia/online-store-data

## 📊 Performed Analyses
### 1️⃣ Data Preprocessing
- Handled missing values
- Removed duplicates
- Converted `InvoiceDate` to datetime
- Added calculated fields (`TotalRevenue`, `YearMonth`, `Hour`)

### 2️⃣ Exploratory Data Analysis (EDA)
- **Sales Trends Over Time:** Monthly sales trends visualized with a line chart
- **Top-Selling Products:** Best-selling products by quantity and revenue
- **Customer Analysis:** Identified high-value customers and repeat vs. one-time buyers
- **Sales by Country:** Bar chart representation of revenue contribution by country

### 3️⃣ Time-Based Insights
- **Sales by Hour of Day:** Identified peak sales hours using a bar chart
- **Seasonality Detection:** Trend analysis based on invoice dates


## 📈 Visualizations
The project includes:

✅ Line charts for sales trends

✅ Bar plots for product & customer analysis

## 🚀 How to Run the Project
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/RetailStoreSalesAnalysis.git
   cd RetailStoreSalesAnalysis
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook RetailStoreSalesAnalysis.ipynb
   ```
4. Run all cells to execute the analysis.

## 🛠 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** for interactive analysis

## 📌 Future Improvements
- Add real-time data streaming support
- Implement predictive sales forecasting using machine learning
- Enhance visualization with interactive dashboards (Plotly, Dash, Power BI)

---
📌 **Author:** Vibhum Sharma  
📧 Contact: vibhum10sharma@gmail.com

# Task 2 - Twitter Sentiment Analysis
🚀 *Analyzing public sentiment on social media using NLP techniques*  

#### Overview
This project, completed during my **Data Science and Analysis internship**, focuses on **Twitter Sentiment Analysis** to understand public opinion on various topics, products, or events. The analysis involves:  
- **Data Preprocessing**: Cleaning and tokenizing text data  
- **Sentiment Extraction**: Classifying tweets as positive, negative, or neutral  
- **Visualization**: Tracking sentiment trends over time  

#### **Tech Stack**  
🔹 Python  
🔹 NLP (Natural Language Processing)  
🔹 Pandas, NumPy  
🔹 Matplotlib, Seaborn  
🔹 Scikit-learn  

#### **Features**  
✅ Preprocessing of raw tweets (removing stopwords, lemmatization, etc.)  
✅ Sentiment classification using NLP techniques  
✅ Visualization of sentiment trends over time  

Run the Jupyter Notebook to explore the analysis and insights.  

#### **Results & Insights**  
- Extracted sentiment scores from tweets  
- Identified trends in public sentiment  
- Gained insights into public reactions towards different topics
- Found whether the tweet is positive or negative

📌 **Author:** Vibhum Sharma  
📧 Contact: vibhum10sharma@gmail.com
