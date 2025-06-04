# 🔍 Pipeline: Cleaned Data from Warehouse (Staging) to Warehouse (Presentation Layer)
 
This pipeline copies Raw data from the **Microsoft Fabric Lakehouse** to the **Fabric Warehouse** using the Copy activity.
 
---
## 🧠 What This Pipeline Does
 
- Takes **filtered and structured** trip data from the staging table
- Loads it into the **final analytics-ready presentation layer**
- This table is used in Power BI or other dashboards

---
 
### 📸 Screenshot of Pipeline
This is a view of the pipeline using the Stored Procedure rather than the Dataflow Gen2. If you're using a Dataflow you can ignore the code for the SP Process Presentation activity

![image](https://github.com/user-attachments/assets/c41be821-d723-4f7c-a84c-996f68be93e2)

---

### ⚙️ Create the dbo.nyctaxi_yellow table

This is the initial empty table so we can load the data from the Dataflow/Stored Procedure acivities
![image](https://github.com/user-attachments/assets/f50a8aa0-8806-4d4f-8c7d-ed333c677d68)

---

### ⚙️ SP Processing Presentation

For the Stored Procedure Activity “SP Processing Presentation ”.

Create the Stored Procedure dbo.process_presentation in the Data Warehouse using the code below.
![image](https://github.com/user-attachments/assets/362eba6d-d674-403d-9388-e0a0fda00797)

---

### ⚙️ SP Loading Presentation Metadata
For the Stored Procedure Activity “SP Loading Staging Metadata”.

Create the Stored Procedure metadata.insert_staging_metadata in the Data Warehouse using the code below.

![image](https://github.com/user-attachments/assets/adde5a03-7c1c-4538-8813-e86b9799c8f6)

![image](https://github.com/user-attachments/assets/d4fc4fbc-ccba-4c7b-b49a-df3f688ea3f4)

