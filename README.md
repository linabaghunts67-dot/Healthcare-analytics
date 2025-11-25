# Healthcare Analytics — Data Cleaning & Exploratory Analysis

This project performs **data cleaning, preprocessing, and initial analytics** on a healthcare dataset containing patient information and medical records.  
The focus is to identify missing values, handle invalid entries, clean categorical columns, and prepare the dataset for future machine learning models.

The entire workflow is implemented inside `Healthcare_Analytics.ipynb`.

---

## 📊 Dataset

The dataset (e.g., `diabetic_data.csv`) contains medical attributes such as:

- Patient demographics  
- Diagnoses  
- Lab results  
- Medication information  
- Readmission status  
- Various coded categorical fields
  
---

## 🧠 What This Project Does

Inside the notebook, I performed a step-by-step data cleaning process:

### 1. **Loaded and inspected the dataset**
- Checked dataset shape, column types, and general structure  
- Identified categorical vs. numerical columns  
- Viewed unique values across multiple fields  

### 2. **Handled missing values**
- Replaced common placeholders (e.g., `"?"`)  
- Applied mode/median/mean imputation where appropriate  
- Ensured no critical feature remained unusable  

### 3. **Cleaned categorical variables**
- Standardized category labels  
- Removed or corrected inconsistent values  
- Verified unique-value distributions  

### 4. **Detected and fixed data-quality issues**
- Checked for nonsensical values (e.g., negative numbers, unknown codes)  
- Cleaned multi-level categorical fields  
- Ensured columns were ready for ML encoding

### 5. **Explored the data**
- Basic visualizations (if included)  
- Distribution analysis  
- Early understanding of patient trends  

---

## 🛠 Technologies Used

- **Python**  
- **pandas** – data cleaning and preprocessing  
- **NumPy** – numerical operations  
- **matplotlib / seaborn** – optional visualizations  
- **Jupyter Notebook**

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
