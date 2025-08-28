# 👨‍💻 Employee & Project Data Analysis (Python + Pandas)

This project demonstrates **data cleaning, transformation, and analysis** using Python and Pandas.  
The dataset includes information about employees, departments, and projects.  

---

## 📊 Tasks Performed  

### ✅ Task 1  
- Read three tables into Pandas dataframes.  
- Saved them as `.csv` files for further processing.  

### ✅ Task 2  
- Handled missing values in the **Project cost** column.  
- Replaced missing values using a **running average (with for loop)**.  

### ✅ Task 3  
- Split `name` column in Employee dataframe into `First Name` and `Last Name`.  
- Dropped the original `name` column.  

### ✅ Task 4  
- Joined **Employee**, **Department**, and **Project** into a single dataframe called `Final`.  

### ✅ Task 5  
- Added a new column `Bonus`.  
- Employees who finished projects received a **5% bonus on project cost**.  

### ✅ Task 6  
- Demoted designation level by 1 for employees with **failed projects**.  
- Deleted employee records where designation level > 4.  

### ✅ Task 7  
- Added **Mr./Mrs. prefix** to the `First Name` column based on gender.  
- Dropped the `Gender` column.  

### ✅ Task 8  
- Promoted designation level by 1 for employees **older than 29 years** (IF condition).  

### ✅ Task 9  
- Computed **total project cost per employee**.  
- Created a new dataframe `TotalProjCost` with `ID`, `First Name`, and `Total Cost`.  

### ✅ Task 10  
- Printed details of employees whose **city names contain the letter "o"**.  

---

## 🛠️ Tech Stack  
- **Python 3.x**  
- **Pandas**  
- **NumPy**  

---
