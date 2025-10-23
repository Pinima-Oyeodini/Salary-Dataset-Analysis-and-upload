![Salary-image](https://github.com/user-attachments/assets/ca8e834a-d667-477c-bd28-74b10d017bc1)


# 💼 Employee Salary Analysis – Excel Dashboard & Insights

## 📊 Project Overview
This project analyzes employee salary data to uncover insights about **compensation trends**, **education level**, **gender differences**, **experience correlation**, and **departmental pay distribution**.

The analysis was done entirely in **Microsoft Excel**, leveraging **Pivot Tables**, **Charts**, and **Correlation Analysis** tools.

---

## 🧩 Dataset Description
The dataset contains the following key fields:

| Column Name | Description |
|--------------|--------------|
| Employee ID | Unique identifier for each employee |
| Job Title | Employee's position or designation |
| Department | Department or business unit |
| Salary | Employee’s annual salary (USD) |
| Education Level | Bachelor's, Master's, or PhD |
| Gender | Male or Female |
| Experience (Years) | Total years of professional experience |
| Age | Employee's age group |

---

## 🎯 Objectives & Key Questions

1. **What is the average salary by job title?**  
2. **How does education level affect salary distribution?**  
3. **What is the gender pay difference across roles?**  
4. **Does experience correlate with higher pay?**  
5. **Which departments or job titles pay the most?**  
6. **Which age group earns the highest average salary?**  
7. **What is the salary distribution across education levels?**

---

## 🔍 Detailed Analysis & Results

### **1️⃣ Average Salary by Job Title**

- **Top 5 Highest Paying Roles:**
  | Job Title | Avg. Salary ($) |
  |------------|-----------------|
  | CEO | 250,000 |
  | CTO | 250,000 |
  | Chief Data Officer | 220,000 |
  | VP of Finance | 200,000 |
  | Director | 200,000 |

- **Interpretation:**  
  Leadership roles (C-suite and Directors) dominate the salary structure.  
  Mid-level technical and management roles earn between **$90,000 – $140,000**, while entry-level positions average **$40,000 – $60,000**.

- **Excel Method:**  
  - Insert Pivot Table → Rows = *Job Title*, Values = *Average of Salary*.  
  - Chart Type: **Bar Chart** or **Sorted Column Chart**.

---

### **2️⃣ Effect of Education Level on Salary**

| Education Level | Average Salary ($) |
|------------------|--------------------|
| Bachelor's | 68,830 |
| Master's | 120,000 |
| PhD | 158,000 |

- **Interpretation:**  
  Salaries increase significantly with education level.  
  Employees holding PhDs earn **~130% more** than those with only a Bachelor’s degree.

- **Excel Method:**  
  - Pivot Table → Rows = *Education Level*, Values = *Average of Salary*.  
  - Chart Type: **Box Plot** or **Clustered Column Chart** for distribution comparison.

---

### **3️⃣ Gender Pay Difference Across Roles**

| Gender | Average Salary ($) |
|---------|--------------------|
| Female | 88,750 |
| Male | 103,152 |

- **Interpretation:**  
  Males earn on average **$14,400 more** than females.  
  The disparity widens in technical and leadership positions (e.g., Project Management and Senior Analyst roles).

- **Excel Method:**  
  - Pivot Table → Rows = *Job Title*, Columns = *Gender*, Values = *Average of Salary*.  
  - Chart Type: **Stacked Column Chart** or **Side-by-Side Bar Chart**.

---

### **4️⃣ Experience vs Salary Correlation**

| Years of Experience | Avg. Salary ($) |
|----------------------|-----------------|
| 0–5 Years | 45,000 – 65,000 |
| 6–10 Years | 80,000 – 100,000 |
| 11–20 Years | 110,000 – 160,000 |
| 21–25 Years | 170,000 – 250,000 |

- **Interpretation:**  
  There is a **strong positive correlation** between experience and salary.  
  Using Excel’s `CORREL()` function between *Experience* and *Salary* yields a correlation ≈ **0.88**, confirming a strong linear relationship.

- **Excel Method:**  
  - Insert Scatter Plot: X = *Experience (Years)*, Y = *Salary*.  
  - Add Trendline → Display Equation and R² value.

---

### **5️⃣ Top Paying Departments / Roles**

| Department | Avg. Salary ($) |
|-------------|-----------------|
| Executive (CEO/CTO/CDO) | 250,000 |
| Finance | 200,000 |
| Operations | 190,000 |
| Research | 190,000 |
| Marketing | 180,000 |

- **Interpretation:**  
  Strategic and research-oriented departments command the highest compensation, suggesting a premium for decision-making and innovation-driven roles.

- **Excel Method:**  
  - Pivot Table → Rows = *Department*, Values = *Average of Salary*.  
  - Chart Type: **Clustered Bar Chart** or **Treemap**.

---

### **6️⃣ Salary by Age Group**

| Age Group | Average Salary ($) |
|------------|--------------------|
| 20–30 | 43,889 |
| 30–40 | 77,643 |
| 40–50 | 136,415 |
| 50–60 | 180,385 |

- **Interpretation:**  
  Salaries steadily increase with age, peaking at ages **50–60**, which aligns with career progression and leadership roles.

- **Excel Method:**  
  - Pivot Table → Rows = *Age Group*, Values = *Average of Salary*.  
  - Chart Type: **Line Chart** or **Area Chart**.

---

### **7️⃣ Salary Distribution Across Education Levels**

- **Trend Observation:**  
  - PhD holders dominate senior and executive-level positions (e.g., Research Director, CTO).  
  - Master’s graduates populate mid-management and technical roles.  
  - Bachelor’s degree holders fill a majority of entry and operational positions.

- **Interpretation:**  
  Education level not only affects salary but also the **type of roles attained**, showing upward mobility with advanced degrees.

- **Excel Method:**  
  - Pivot Table → Rows = *Job Title*, Columns = *Education Level*, Values = *Average of Salary*.  
  - Chart Type: **Heatmap (Conditional Formatting)** for salary intensity visualization.

---

## 📈 Summary of Key Insights

- **Strong correlation (r ≈ 0.88)** between experience and salary.  
- **PhD holders** earn ~2.3× more than Bachelor's degree holders.  
- **Gender gap** exists (~14% difference), more pronounced in senior roles.  
- **Executive leadership** positions dominate salary scales.  
- **Age 50–60** employees earn the most on average.

---

## 🧮 Tools Used

- **Microsoft Excel 365**
  - Pivot Tables
  - Pivot Charts
  - Conditional Formatting
  - CORREL() Function
  - Trendlines & R² Visualization

---


---

## 🧠 Author
**Pinima Oyeodini**  
📧 pinimapreciousdennis@gmail.com 
   


