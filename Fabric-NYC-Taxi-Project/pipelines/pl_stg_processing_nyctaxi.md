# 🔍 Pipeline: Raw Data (.parquet) from Lakehouse to Warehouse
 
This pipeline copies Raw data from the **Microsoft Fabric Lakehouse** to the **Fabric Warehouse** using the Copy activity.
 
---
 
### 📸 Screenshot of Pipeline
 
 
![image](https://github.com/user-attachments/assets/8710bf0e-e4c5-4163-8f54-a418ab709a64)

---

### Latest Processed Data
For the Script Activity “Latest Processed Data”
![image](https://github.com/user-attachments/assets/7d1c529c-8770-4586-acb7-c1550ecc9cae)

---

### v_date
Pipeline expression for v_date Set Variable activity
![image](https://github.com/user-attachments/assets/ed660917-b5b4-42e9-8491-1c9e38225417)

---

### Copy to Staging

Pre Copy Script

![image](https://github.com/user-attachments/assets/b1f3f0ed-eae0-4299-b961-b8fc90f4def5)

---

### v_end_date
Pipeline expression for v_end_date Set Variable activity
![image](https://github.com/user-attachments/assets/3d0f3cd8-9734-4f9d-8885-72c1c80eb5b5)

---

### SP Removing Outlier Dates
For the Stored Procedure Activity “SP Removing Outlier Dates”.

Create the Stored Procedure stg.data_cleaning_stg in the Data Warehouse using the code below.

![image](https://github.com/user-attachments/assets/440b4da7-baa3-4135-b9f9-b401cddf1a2b)

![image](https://github.com/user-attachments/assets/7be46342-5e31-4057-a0e8-bcf4c719bbae)

---

### SP Loading Staging Metadata
For the Stored Procedure Activity “SP Loading Staging Metadata”.

Code to create the metadata.processing_log table.

![image](https://github.com/user-attachments/assets/666a380b-63b4-4fa6-9d3e-042e41b593fa)

Created the Stored Procedure metadata.insert_staging_metadata in the Data Warehouse using the code below.
![image](https://github.com/user-attachments/assets/c1d7a8a1-5ade-4854-8ef9-d4e6b2017bb6)

![image](https://github.com/user-attachments/assets/c75d7d09-8f89-4de8-b92e-6f3d482d1f0c)




