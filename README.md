
💻 Laptop Price Analysis & Predictive Modeling
📌 Project Overview
This project provides a comprehensive analysis of the global laptop market, exploring the relationships between hardware specifications and pricing. Beyond descriptive analytics, the project includes a high-accuracy machine learning model to predict laptop prices based on technical configurations.

🎯 Objectives
Analyze the impact of hardware components (RAM, Storage, GPU) on market price.

Compare brand performance regarding battery life and portability.

Develop a predictive model to estimate laptop prices with high precision.

Create an interactive dashboard for data-driven consumer insights.

📊 Data Sources
The dataset contains over 11,700 records across 10 major laptop brands.

Features include Processor type, RAM, Storage (SSD/HDD), Resolution, Operating System, Weight, and Battery Life.

🧹 Data Pre-processing & Feature Engineering
Data Cleaning: Handled missing values and standardized categorical specifications.

Log Transformation: Applied np.log1p to the target variable (Price) to handle skewness and improve model convergence.

Feature Scaling: Used StandardScaler for numerical columns and OneHotEncoder for categorical features.

New Features Created:

Price per RAM: Ratio of cost to memory capacity.

RAM x Processor Score: An interaction feature to capture performance synergy.

Categorical Binning: Created "Weight Category" and "Battery Category" for better grouping.

🏗️ Data Modeling (Power BI)
Built a robust Star Schema to optimize dashboard performance:

Fact Table: laptop_prices (containing core metrics and prices).

Dimension Tables: dim_processor, dim_storage, and dim_resolution.

Established 1-to-many relationships using unique keys and performance scores.

📈 Key Insights
Price Drivers: Storage type (SSD vs HDD) and Screen Resolution (4K vs FHD) remain the primary factors in price variance.

Battery Life: Lenovo and HP lead the average battery life rankings (approx. 8.12 hours).

Market Distribution: Windows is the "Most Used OS," though macOS and FreeDOS models hold significant niche price points.

Performance vs. Price: A clear linear correlation exists between higher-tier processors (Intel i9 / Ryzen 9) and premium pricing tiers.

🔮 Machine Learning & Forecasting
Developed a predictive pipeline using Scikit-Learn.

Model Used: HuberRegressor (robust to outliers) within a ColumnTransformer pipeline.

Performance: - Achieved an R² Score of 0.97 (97% accuracy) on the testing set.

Successfully minimized error margins for high-end gaming and professional laptops.

📌 Key KPIs
Total Units: 11,771

Price Range: $280 – $10,808

Average Battery Life: 8.03 Hours

Model Accuracy: 97%

📊 Dashboard
An interactive multi-page Power BI dashboard was developed:

Overview Page: High-level metrics, price distribution by processor, and brand comparison tables.

Details Page: Deep dives into average price by storage, RAM distribution (Doughnut chart), and battery life trends by processor type.

Slicers: Dynamic filtering by GPU, Brand, Resolution, and Storage type.

🛠️ Tools Used
Python: Pandas, NumPy, Scikit-Learn (ML Pipeline).

Power BI: DAX Measures, Data Modeling (Star Schema), Power Query.

Microsoft Excel: Initial data exploration and cleaning.

👥 Team
Ibrahim Ahmed (Data Analyst & ML Developer)

Omar Abdelbaset

Malak Zidan

Arwa Youssef

Aya Taha

🚀 Initiative
Digital Egypt Pioneers Initiative (DEPI)

📷 Dashboard Preview
📬 Contact
GitHub: Ebrahim-Azab

LinkedIn: [Your LinkedIn Profile Link]

وضح انه كان final project مع orange

تعديل ممتاز، إضافة اسم Orange كشريك في المشروع النهائي (Final Project) بيعطي ثقل كبير للـ Readme.

إليك النسخة المعدلة مع دمج Orange Digital Center ضمن سياق المشروع:

💻 Laptop Price Analysis & Predictive Modeling
📌 Project Overview
This is the Final Project developed in collaboration with Orange Digital Center (ODC). The project provides a comprehensive analysis of the global laptop market, exploring the relationships between hardware specifications and pricing. Beyond descriptive analytics, it includes a high-accuracy machine learning model to predict prices based on technical configurations.

🎯 Objectives
Analyze the impact of hardware components (RAM, Storage, GPU) on market price.

Compare brand performance regarding battery life and portability.

Develop a predictive model to estimate laptop prices with high precision.

Create an interactive dashboard for data-driven consumer insights.

📊 Data Sources
The dataset contains over 11,700 records across 10 major laptop brands.

Features include Processor type, RAM, Storage (SSD/HDD), Resolution, Operating System, Weight, and Battery Life.

🧹 Data Pre-processing & Feature Engineering
Data Cleaning: Handled missing values and standardized categorical specifications.

Log Transformation: Applied np.log1p to the target variable (Price) to handle skewness.

Feature Scaling: Used StandardScaler for numerical columns and OneHotEncoder for categorical features.

New Features: Created interaction terms like RAM x Processor Score and specialized binnings for Weight and Battery life.

🏗️ Data Modeling (Power BI)
Built a robust Star Schema to optimize dashboard performance:

Fact Table: laptop_prices (containing core metrics and prices).

Dimension Tables: dim_processor, dim_storage, and dim_resolution.

Established 1-to-many relationships using unique keys and performance scores.

📈 Key Insights
Price Drivers: Storage type (SSD vs HDD) and Screen Resolution (4K vs FHD) are the primary factors in price variance.

Battery Life: Lenovo and HP lead the average battery life rankings (approx. 8.12 hours).

Market Distribution: Windows is the "Most Used OS," while premium brands like Apple and Razer command the highest average price points.

🔮 Machine Learning & Forecasting
Developed a predictive pipeline using Scikit-Learn.

Model Used: HuberRegressor (robust to outliers) within a ColumnTransformer pipeline.

Performance: - Achieved an R² Score of 0.97 (97% accuracy) on the testing set.

Successfully minimized error margins for high-end gaming and professional laptops.

📌 Key KPIs
Total Units: 11,771

Price Range: $280 – $10,808

Average Battery Life: 8.03 Hours

Model Accuracy: 97%

📊 Dashboard
An interactive multi-page Power BI dashboard was developed:

Overview Page: High-level metrics, price distribution by processor, and brand comparison tables.

Details Page: Deep dives into average price by storage, RAM distribution, and battery life trends.

Slicers: Dynamic filtering by GPU, Brand, Resolution, and Storage type.

🛠️ Tools Used
Python: Pandas, NumPy, Scikit-Learn (ML Pipeline).

Power BI: DAX Measures, Data Modeling (Star Schema), Power Query.

Microsoft Excel: Initial data exploration and cleaning.

📬 Contact
GitHub: Ebrahim-Azab
LinkedIn: [https://www.linkedin.com/in/ibrahim-ahmed-azab/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BNpSJ%2BZ4iSCmmgv3NDvT29A%3D%3D]
