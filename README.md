# Programming Language Trends on StackOverflow

This project analyzes how the popularity of programming languages has evolved over time based on StackOverflow post data from 2008 onward.  
Using Pandas and Matplotlib, I reshaped the dataset, smoothed it with rolling averages, and visualized long-term usage patterns for languages like Python, Java, C++, and Swift.

## 🔗 Dataset

The data contains monthly counts of StackOverflow questions tagged with different programming languages.  
(Data source: StackOverflow Trends CSV export)

## 📊 Key Steps

- Loaded and cleaned the raw CSV  
- Transformed it into time-series format using pivot  
- Counted total posts and active months per language  
- Filled missing values and plotted clean trendlines  
- Applied a 12-month rolling average to smooth time series

## 🛠️ Tools Used

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook

## 📌 Insight

Python shows rapid growth from 2012 onward, eventually overtaking Java and other older languages. Swift appears around 2014 and shows a fast upward trend initially.

---

Feel free to explore or fork this project.
