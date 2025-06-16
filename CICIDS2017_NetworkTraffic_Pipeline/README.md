## 🛡️ CICIDS2017 Network Traffic - Python Data Engineering Pipeline
 
This project demonstrates a data engineering pipeline built using the CICIDS2017 intrusion detection dataset. The goal is to simulate real-world handling of network traffic logs, clean and enrich the data, and prepare it for further analysis or machine learning.
 
---
## 📂 Dataset Source
> ⚠️ Raw dataset files are not included due to size constraints.  
> 📁 Please download the dataset from:  
> [CICIDS2017 Official Source](https://www.unb.ca/cic/datasets/ids-2017.html)
---
 
## ⚙️ Steps Performed
 
1. **Data Wrangling**: Handled missing/null/infinite values.
2. **Feature Engineering**: Created features like byte ratios, flow duration, and packet counts.
3. **Security Insights**:
   - Label distribution chart
   - Top attacker IPs
   - Protocol usage patterns
   - Correlation heatmap of engineered features
4. **Export**: Final dataset exported for use in BI tools or ML models.
 
---
 
## 📊 Tools & Libraries
 
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
 
---
 
## 📁 Project File
 
- `CICIDS2017_Data_Engineering_Pipeline.ipynb` – Full pipeline with code, cleaning, feature engineering, and visualizations
 
---

## ✅ Instructions to Run
 
1. Download any sample `.csv` files (e.g., `Friday-WorkingHours-Afternoon-DDos.csv`) from the CICIDS site
2. Place it in a `data/` folder locally
3. Open the notebook in Jupyter
4. Follow each cell step-by-step — from data loading to final export

---
