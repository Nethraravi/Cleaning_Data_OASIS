🧹 Data Cleaning Project | OASIS Infobyte Internship
📌 Project Overview

This project was completed as part of my OASIS Infobyte Data Science Internship.
The main objective was to clean and preprocess raw Airbnb NYC data to ensure accuracy, consistency, and reliability for future analysis and visualization.

Data cleaning is a crucial part of the data science workflow — it transforms messy, unstructured data into a usable and trustworthy dataset.


📊 Dataset

Dataset Name: AB_NYC_2019.csv

Source: Airbnb NYC Open Data

Description: Contains detailed information on Airbnb listings such as price, location, room type, number of reviews, and availability.


🧰 Tools & Technologies Used
Tool / Library	Purpose
Python	Core programming language
Pandas	Data cleaning, manipulation & transformation
Matplotlib	Visualization and outlier analysis
Google Colab / Jupyter Notebook	Development environment


🧩 Steps Performed
1️⃣ Data Inspection

Loaded dataset using Pandas.

Checked for null values, duplicates, and incorrect data types.

Understood overall structure using df.info() and df.describe().

2️⃣ Missing Data Handling

Filled missing values in reviews_per_month with 0.

Retained missing last_review entries (as they represent unreviewed listings).

3️⃣ Duplicate Removal

Detected and removed duplicate rows to ensure data integrity.

4️⃣ Standardization

Cleaned and formatted columns for consistent naming and units.

Converted text data to lowercase and ensured correct numeric formats.

5️⃣ Outlier Detection & Fixing

Visualized outliers using scatter plots and boxplots.

Removed unrealistic values:

Price > 1000 USD

Minimum nights > 365


6️⃣ Visualization

Created insightful and colorful visualizations to understand data distribution:

Scatter plot: Price vs Minimum Nights

Histogram: Price distribution before & after cleaning

Bar chart: Average price per neighborhood group


🎨 Sample Visualizations
Visualization	Description
📈 Scatter Plot	Shows relationship between price and minimum_nights after fixing outliers.
📊 Histogram	Compares price distribution before and after cleaning.
🗺️ Bar Chart	Displays average price per neighborhood group.
🧾 Post-Cleaning Summary
Step	Action	Result
Missing Values	Filled & standardized	✅ Clean
Duplicates	Removed	✅ Unique records
Outliers	Fixed using rules (price ≤ 1000, nights ≤ 365)	✅ Realistic data
Data Consistency	Ensured across all columns	✅ Standardized
Visualization	Created for better understanding	✅ Insightful visuals


💡 Key Insights

Most Airbnb listings in NYC are under $500.

Manhattan has the highest average listing prices.

Typical stays are under 10 nights, confirming short-term rental trends.

Outlier removal and missing value handling greatly improved dataset reliability.
