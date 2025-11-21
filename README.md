# 🌍 Languages:
- 🇬🇧 English (current)
- 🇷🇺 [Русская версия](README_RU.md)

# 📊 Online Retail Analysis Project  
This project presents an exploratory data analysis (EDA) of the **Online Retail** dataset using Python, Pandas, and Matplotlib.  
It demonstrates skills in data cleaning, business analytics, visualization, and working with real-world e-commerce data.

## 🛠️ Tools & Libraries
- Python 3  
- Pandas  
- Matplotlib  
- Colab

## 📁 Dataset
**Online_Retail.csv** – real-world e-commerce transactional data containing:

- Invoice information  
- Product descriptions  
- Quantities and prices  
- Customer IDs  
- Countries  
- Order timestamps  

## 📊 Project Features

### ✔️ Data Cleaning
- Removed refund transactions (InvoiceNo containing **"C"**)  
- Removed negative prices and quantities  
- Created **TotalPrice** = UnitPrice × Quantity  
- Converted timestamps to datetime  
- Added monthly periods for time-based analysis  

### ✔️ Visualizations
- **Top 10 Most Purchased Products**  
- **Monthly Revenue Dynamics**  
- **Top 10 Customers by Revenue**  
- **Sales by Country (with & without UK)**  
- **Top Country Sales Pie Charts**  
- **Average Check by Month**

## 💡 Insights

- 🇬🇧 The United Kingdom generates the majority of all sales  
- 📦 Best-selling products are small, fast-moving items with high purchase frequency  
- 📈 Sales show visible monthly seasonality  
- 💸 Average order value varies significantly between months  
- 🧍‍♂️ A small group of customers contributes a large share of revenue  

## 🚀 How to Run

1. Clone the repository:
  git clone https://github.com/pompeedu/online-retail-analysis.git
2. Install dependencies:
  pip install pandas matplotlib
3. Place Online_Retail.csv in the project folder
4. Run the Python script or Jupyter notebook

## 🧠 Author
Firuzjon Qurbonov – Aspiring Data Scientist from Russia  
📫 Contact: [Telegram/@pompeedu](https://t.me/pompeedu) or [firuzjonkurbonov735700@gmail.com](mailto:firuzjonkurbonov735700@gmail.com)
