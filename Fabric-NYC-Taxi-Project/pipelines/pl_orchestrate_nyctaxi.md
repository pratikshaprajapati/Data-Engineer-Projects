## 🔍 Pipeline: Orchestrator for End-to-End NYC Taxi Data Load(Staging to Presentation)
 
This pipeline copies Raw data from the **Microsoft Fabric Lakehouse** to the **Fabric Warehouse** using the Copy activity.
 
---

### 🧠 What This Pipeline Does
 
- Acts as the **main scheduler or parent pipeline**
- Ensures end-to-end data readiness for reporting
- Hepls manage dependencies and failure handling centrally

---
 
#### 📸 Screenshot of Pipeline
 
 
![image](https://github.com/user-attachments/assets/2441f1af-3020-41ac-aa21-5e02e6c555f6)


---

#### ⚙️ Notes
-You can add **emial/Teams alert** in case of failure.
-Userful for **production scheduling** and **retires**.
