# Bitcoin-price-prediction

### **📌 Project Overview**

This project performs Exploratory Data Analysis (EDA) on Bitcoin price data to uncover trends, volatility, trading volume variations, and seasonality. The analysis includes visualizing price trends, identifying outliers, detecting anomalies, and understanding the correlation between trading volume and price fluctuations. Additionally, this project emphasizes statistical techniques such as moving averages, hypothesis testing, and time series decomposition to highlight deeper insights.

### **📂 Dataset**

The dataset contains historical Bitcoin price information with the following key columns:

**Timestamp** – Date and time of recorded price.

**Open** – Opening price of Bitcoin for the given period.

**High** – Highest price within the period.

**Low** – Lowest price within the period.

**Close** – Closing price.

**Volume** – Total trading volume.

**Hour** – Extracted hour from the timestamp to analyze intraday trends.

**Month** – Extracted month to observe seasonal patterns.

**Year** – Extracted year to identify long-term trends.

### 📊 Key Questions Answered

**1️⃣ Bitcoin Price Trends & Volatility**

How has Bitcoin price evolved over time?

What were the highest and lowest Bitcoin prices recorded?

When were the most volatile periods in Bitcoin history?

What are the moving averages (e.g., 7-day, 30-day) of Bitcoin prices?

**2️⃣ Trading Volume & Market Activity**

How does trading volume vary over time?

How does trading volume change monthly and yearly?

What time of day has the highest trading volume?

Is there a statistical correlation between volume and price changes?

**3️⃣ Seasonality & Patterns**

Does Bitcoin exhibit seasonal trends?

What is the correlation between price change and trading volume?

Do certain days of the week have more price movements?

Can we detect cyclical patterns using time series decomposition?

**4️⃣ Extreme Events & Anomalies**

Were there sudden crashes or price spikes?

What were the top 5 biggest single-day gains & losses?

How do price trends vary by time of day?

Are there statistically significant outliers in the price movement?

**5️⃣ Comparisons & Correlations**

How are Open, High, Low, and Close prices correlated?

Does trading volume impact price changes?

Are there any outlier transactions with extremely high volume?

How do hypothesis tests confirm relationships between price movements and trading volume?

### ⚙️ Installation & Setup

To run the analysis, install the required libraries:

**pip install pandas matplotlib seaborn scipy statsmodels**

Clone the repository and navigate to the project folder:

**git clone https://github.com/yourusername/bitcoin-eda.git**

**cd bitcoin-eda**

### 📝 Usage



