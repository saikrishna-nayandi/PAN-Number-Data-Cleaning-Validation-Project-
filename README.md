readme_content = """
# 📝 PAN Number Validation using Python  

## 📌 Objective
You are tasked with **cleaning and validating a dataset** containing the **Permanent Account Numbers (PAN)** of Indian nationals. The goal is to ensure that each PAN number adheres to the official format and is categorized as either **Valid** or **Invalid**.  

The dataset used is:  
**`PAN Number Validation Dataset.xlsx`**

---

## 🛠️ Instructions

### 1️⃣ Data Cleaning and Preprocessing
- **Handle missing data:** Identify missing PAN numbers and remove or impute them as necessary.  
- **Check for duplicates:** Remove any duplicate PAN numbers.  
- **Trim spaces:** Remove leading or trailing spaces in PAN numbers.  
- **Correct letter case:** Ensure PAN numbers are in **uppercase**.  

### 2️⃣ PAN Format Validation
A valid PAN number follows the format: `AAAAA1234A`  
- **Length:** Exactly 10 characters  
- **First 5 characters:** Alphabetic (uppercase)  
  - ✅ **No adjacent repeated letters** (e.g., `AABCD` invalid)  
  - ✅ **Cannot form a sequence** (e.g., `ABCDE` invalid)  
- **Next 4 characters:** Numeric digits  
  - ✅ **No adjacent repeated digits** (e.g., `1123` invalid)  
  - ✅ **Cannot form a sequence** (e.g., `1234` invalid)  
- **Last character:** Alphabetic (uppercase)  

**Example of valid PAN:** `AHGVE1276F`

---

### 3️⃣ Categorization
- **Valid PAN:** Matches the format above.  
- **Invalid PAN:** Does not match the format, incomplete, or contains non-alphanumeric characters.  

---

## ✅ Tasks Completed
- Validated PAN numbers based on the official format.  
- Created two categories:
  - **Valid PAN**
  - **Invalid PAN**
- Generated a **summary report**:
  - Total records processed
  - Total valid PANs
  - Total invalid PANs
  - Total missing or incomplete PANs  

---

## 📂 Technology Used
- **Python** 🐍  
- **Jupyter Notebook** 📓  
- **Pandas** 📊  
- **NumPy** 🔢  

---
