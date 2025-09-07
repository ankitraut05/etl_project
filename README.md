# 🚀 ETL Pipeline Project (Python + MySQL)

This project demonstrates a simple **ETL (Extract, Transform, Load) pipeline** built using Python, Pandas, and MySQL.  
It is designed to showcase **Data Engineering skills** such as data extraction, transformation, and loading into a relational database.

---

## 📌 Project Overview
The ETL pipeline follows these steps:

1. **Extract** → Reads raw employee data from a CSV file (`employees.csv`).  
2. **Transform** → Cleans and prepares the data:  
   - Removes rows with missing employee ID or email  
   - Fills missing last names with `"Unknown"`  
   - Removes invalid emails (without `@`)  
   - Fills missing salary with average salary  
   - Converts department names to uppercase  
3. **Load** → Inserts the transformed data into a **MySQL database** (`Employee.sql`).

---

