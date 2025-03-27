📱 Smartphone Data Analysis: Insights & Visualizations
📌 Project Overview
This project explores a comprehensive smartphone dataset to uncover key insights using data cleaning, univariate, bivariate, and multivariate analysis. The dataset includes various smartphone attributes such as price, brand, processor, RAM, storage, battery capacity, camera specifications, and more.

We aim to answer crucial questions like:
✅ How do different smartphone brands compare in pricing?
✅ Does more RAM always mean a higher price?
✅ How does battery capacity vary across brands?
✅ What are the key trends in smartphone specifications over time?

📊 Analysis Performed
1️⃣ Data Cleaning & Preprocessing
✔️ Handled missing values strategically (mode, median, or manual input).
✔️ Standardized and formatted data for better consistency.
✔️ Removed anomalies and outliers.

2️⃣ Univariate Analysis
✔️ Explored the distribution of price, RAM, battery capacity, and other features using histograms, box plots, and KDE plots.
✔️ Identified key trends in individual columns (e.g., dominant brands, most common RAM sizes).

3️⃣ Bivariate Analysis
✔️ Analyzed relationships between key variables such as:

Price vs. Brand Name (Which brands dominate premium & budget categories?)

Price vs. RAM & Storage (Is more RAM always better?)

Price vs. Battery Capacity (Do bigger batteries mean costlier phones?)

Price vs. 5G Support (How does 5G impact price?)

✔️ Used scatter plots, bar plots, box plots, and heatmaps to visualize insights.

4️⃣ Multivariate Analysis
✔️ Explored the combined effect of multiple features using:

3D scatter plots for visualizing price, RAM & internal memory together.

Facet grids to analyze trends across different processor brands.

🚀 Key Insights & Findings
📌 Apple & Snapdragon-powered devices dominate the premium segment, while MediaTek & Unisoc are popular in budget-friendly smartphones.
📌 Higher RAM & storage generally increase price, but certain brands offer better value-for-money options.
📌 5G smartphones are typically more expensive, but budget-friendly 5G models are emerging.
📌 Battery size is not necessarily a price determinant—many budget devices offer large batteries.

📂 Project Files
📄 smartphone_cleaned_v5.csv → Cleaned dataset used for analysis.

📜 EDA.ipynb → Jupyter Notebook with complete exploratory data analysis.

📊 Visualizations/ → Folder containing all generated plots & graphs.

📌 How to Use
1️⃣ Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-repo/smartphone-analysis.git
cd smartphone-analysis
2️⃣ Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn plotly
3️⃣ Run the analysis in Jupyter Notebook or Google Colab.

💡 Future Enhancements
🔹 Predict smartphone prices using Machine Learning models.
🔹 Develop an interactive dashboard for real-time data exploration.
🔹 Add more datasets to analyze smartphone trends over different years.

📢 Connect & Feedback
📧 Have suggestions or feedback? Feel free to reach out or contribute! 🚀
