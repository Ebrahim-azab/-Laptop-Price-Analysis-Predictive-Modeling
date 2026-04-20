💻 Laptop Price Analysis & Predictive Modeling  

---

## 📌 Project Overview  
This is a Final Project developed in collaboration with Orange Digital Center (ODC).  
The project provides a comprehensive analysis of the global laptop market, focusing on how hardware specifications influence pricing. It also includes a high-performance machine learning model to predict laptop prices based on technical configurations.

---

## 🎯 Objectives  
- Analyze the impact of hardware components (RAM, Storage, GPU) on laptop pricing  
- Compare brand performance in terms of battery life and usability  
- Develop a predictive model for accurate laptop price estimation  
- Build an interactive dashboard for business and consumer insights  

---

## 📊 Data Sources  
- Dataset containing 11,700+ laptop records  
- 10 major global laptop brands  
- Features include: Processor, RAM, Storage (SSD/HDD), GPU, Screen Resolution, OS, Weight, Battery Life  

---

## 🧹 Data Pre-processing & Feature Engineering  
- Handled missing values and standardized all categorical features  
- Applied **log transformation (np.log1p)** to reduce price skewness  
- Used **StandardScaler** for numerical features  
- Applied **OneHotEncoder** for categorical variables  
- Created engineered features such as:  
  - RAM × Processor Score interaction  
  - Battery Life grouping (binned categories)  
  - Weight optimization categories  

---

## 🏗️ Data Modeling (Power BI)  
A Star Schema was built to optimize performance and analysis:  

- **Fact Table:** laptop_prices (core metrics + price)  
- **Dimension Tables:**  
  - dim_processor  
  - dim_storage  
  - dim_resolution  

Relationships were structured using unique keys to ensure efficient filtering and reporting.

---

## 📈 Key Insights  
- Storage type (SSD vs HDD) and screen resolution (FHD vs 4K) are the strongest price drivers  
- Lenovo and HP show the best average battery performance (~8.12 hours)  
- Windows dominates market usage across all brands  
- Premium brands like Apple and Razer lead in highest price segments  

---

## 🔮 Machine Learning Model  
- Built an end-to-end ML pipeline using Scikit-Learn  
- Model: **HuberRegressor** (robust to outliers)  
- Achieved performance:  
  - **R² Score: 0.97 (97% accuracy)**  
- Strong predictive performance across gaming and high-end laptops  
- Reduced error margins significantly for price estimation  

---

## 📌 Key KPIs  
- Total Units: 11,771  
- Price Range: $280 – $10,808  
- Average Battery Life: 8.03 Hours  
- Model Accuracy: 97%  

---

## 📊 Dashboard (Power BI)  
An interactive multi-page dashboard was developed:  

- **Overview Page:**  
  - Key KPIs  
  - Price distribution by processor  
  - Brand comparison  

- **Details Page:**  
  - Price vs Storage analysis  
  - RAM distribution  
  - Battery life trends  

- **Filters/Slicers:**  
  - Brand  
  - GPU  
  - Storage Type  
  - Resolution  

---

## 🛠️ Tools Used  
- Python (Pandas, NumPy, Scikit-Learn)  
- Power BI (DAX, Power Query, Data Modeling)  
- Microsoft Excel (Initial cleaning & exploration)  

---

## 🎓 Final Project Partners  
- Orange Digital Center (ODC)  
---

## 📬 Contact  
- GitHub: Ebrahim-Azab  
- LinkedIn: [https://www.linkedin.com/in/ibrahim-ahmed-azab/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BNpSJ%2BZ4iSCmmgv3NDvT29A%3D%3D]
