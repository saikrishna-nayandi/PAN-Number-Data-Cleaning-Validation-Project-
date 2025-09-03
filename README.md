readme_content = """
# 📝 PAN Number Validation using Python  

This project demonstrates how to **clean, validate, and analyze Indian PAN Numbers** using **Python (Pandas + Regex + Matplotlib)**.  

It ensures that PAN data follows the correct format and eliminates invalid or suspicious entries (e.g., duplicates, sequential patterns, or adjacent repetitions).  

---

## 🚀 Features  
- ✅ Data Cleaning: remove blanks, duplicates, formatting issues  
- ✅ PAN Validation Rules:  
  - Correct format (`AAAAA9999A`)  
  - No adjacent character repetition (e.g., `AABCD1234E ❌`)  
  - No sequential patterns (e.g., `ABCDE1234F ❌`)  
  - Length must be **10 characters**  
- ✅ Generates a **summary report** (Valid, Invalid, Missing counts)  
- ✅ Exports results to Excel with detailed validation status  
- ✅ Visualizes results with **Bar & Pie charts** using Matplotlib  

---

## 📂 Project Structure  

├── PAN Number Validation Dataset.xlsx # Input dataset
├── PAN VALIDATION RESULT.xlsx # Output (Validations + Summary)
├── pan_validation.ipynb # Jupyter Notebook with full workflow
└── README.md # Project documentation

📊 Output Summary

Excel File: PAN VALIDATION RESULT.xlsx

Sheet 1: PAN Validations (row-wise status)

Sheet 2: Summary Report

Charts: Bar and Pie chart showing distribution of:

✅ Valid PANs

❌ Invalid PANs

⚠ Missing PANs
