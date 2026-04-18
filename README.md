**🛒 E-Commerce Data Handling and Visualization**

"Transforming raw, messy transaction logs into actionable business insights."
📌 Project Overview
This project focuses on data cleaning e-commerce transaction records to understand purchasing patterns and customer spending behavior. The raw dataset contains various features such as customer demographics, product categories, and transaction financials, alongside missing values and data type anomalies.
The core of this project involves building a data cleaning pipeline and generating visualizations to extract meaningful, data-driven insights.
🎯 Objectives
To systematically clean and preprocess the dataset.
To handle missing values and correct string-to-numeric formatting issues.
To analyze purchasing volumes and category-specific spending trends.
To translate complex data into clear visual graphs.
🛠️ Technologies Used
Python (Core logic)
Pandas (Data manipulation, cleaning, and aggregation)
Matplotlib (Programmatic data visualization)
Jupyter Notebook (Interactive development environment)
📂 Dataset Details
Dataset: E-Commerce Transaction Dataset (ecommerce_df.csv)
Size: 55,000 Rows × 12 Columns
Characteristics: Contains missing values, string-formatted currency anomalies, and diverse real-world transaction data.
⚙️ Data Cleaning Pipeline
Imputation: Handled missing promotional data in the Discount Name column.
Type Conversion: Formatted string-based currency data by stripping commas and forcefully converting them to numeric float values (Net Amount).
Datetime Parsing: Converted standard text dates into native Python Datetime objects for temporal analysis.
Data Integrity Check: Filtered out invalid entries (e.g., negative purchase amounts) and permanently dropped duplicate records to ensure analysis accuracy.
📊 Data Visualization Highlights
The following programmatic visualizations were generated using Matplotlib:
Category Popularity: A bar chart detailing the total number of purchases per product category.
Spend Distribution: A histogram visualizing the frequency distribution of net purchase amounts.
Demographic Spending: A bar chart comparing the average net purchase amount across different genders.
📈 Key Insights
Top Categories: Customers spend the most on average in the Toys & Games and Sports & Fitness categories.
Average Spend: The average net purchase amount across the entire dataset sits at roughly 2,909 INR.
Lowest Spend: Clothing represents the category with the lowest average spend per transaction.
🚀 Future Scope
Predictive Modeling: Training a Machine Learning classifier to predict whether a specific demographic is likely to use a discount code.
Customer Segmentation: Utilizing clustering algorithms (like K-Means) to group similar buying behaviors.
📁 Repository Structure
├── ecommerce_df.csv          # The raw, uncleaned dataset
├── cleaned_ecommerce_df.csv  # The final processed dataset 
├── ecommerce_analysis.ipynb  # Jupyter Notebook containing all code & charts
└── README.md                 # Project documentation
Conclusion
This project successfully demonstrates how foundational data wrangling and visualization techniques can be applied to real-world e-commerce datasets to identify hidden patterns and extract highly useful business insights.
👤 Author
Aman Yadav 
BCA (Data Science & Artificial Intelligence), 4th Semester
📎 Note
This project is developed for academic purposes as part of Data Science coursework.
