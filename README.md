# 📊 Sales Data Analysis Project 
Exploratory Data Analysis | Sales Data Analysis | E-commerce Data Analysis
 
## 📝 Overview  
This project performs **Exploratory Data Analysis (EDA)** on sales data to uncover patterns, detect outliers, and generate business insights.  
The analysis was conducted in Python using Pandas, NumPy, Matplotlib, Seaborn, and Plotly for interactive visualizations.  

## 📂 Project Files  
- **[`Project_1.ipynb`](Project_1.ipynb)** → Jupyter Notebook with full analysis & visualizations  
- **[`Project_1.pdf`](Project_1.pdf)** → Exported PDF report (easy to read without running code)  
- **`data.csv`** → Dataset used in the project  
- **`requirements.txt`** → List of Python dependencies
  
## 📊 Dataset  
- **Rows:** ~ 9994 Rows
- **Columns:** Row ID, Order ID,             
  Order Date,  
  Ship Date,       
  Ship Mode,        
  Customer ID,      
  Customer Name,    
  Segment,          
  Country,          
  City,             
  State,            
  Postal Code,      
  Region,           
  Product ID,       
  Category,         
  Sub-Category,     
  Product Name,     
  Sales,            
  Quantity,         
  Discount,         
  Profit,           
  Month,            
  Year,           
  Day,              
  Time Taken,       
  Profit Margin, 
- **Description:** Contains monthly sales transactions across multiple categories.  

## 🛠️ Data Cleaning & Preprocessing  
- Removed duplicates and handled missing values  
- Treated outliers using **IQR/Z-score methods**  
- Standardized categorical text fields (case, spacing, typos)  
- Converted date/month attributes into usable formats  

---

## 📈 Analysis & Visualizations  
- **Monthly Sales Trends** → Line plots showing seasonality and peak months  
- **Category-wise Sales Segregation** → Bar charts highlighting top revenue categories  
- **Outlier Detection** → Interactive **boxplots & scatter plots with Plotly**  

## 💡 Key Insights  
- Category **A** contributed to ~**45% of revenue** consistently  
- **Q4** showed strong seasonal demand (holiday effect)  
- Outliers corresponded to **bulk orders**, not errors → important for forecasting  

## 🚀 Next Steps  
- Extend to **time-series forecasting** (ARIMA / Prophet)  
- Build an interactive **dashboard** using Streamlit or Power BI  
- Perform **customer/region segmentation** if detailed data available  

## 📂 Project Structure  
- data.csv ##Dataset
- Project_1.ipynb **Main Jupiter Notebook**
- Project_1.pdf **Exported Pdf File Report**
- requirements.txt **Dependencies**
- Readme.md **Project Report (This File)**
