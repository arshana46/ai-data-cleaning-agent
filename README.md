# AI Data Cleaning Agent

**Project Type:** Freestyle Track – AI Agents Intensive Capstone  
**Author:** Arshana N  
**Date:** November 2025  

---

## Overview
This project demonstrates an **AI Data Cleaning Agent** that automatically cleans any CSV dataset. The agent simplifies the data preprocessing process by handling common tasks like missing values, duplicates, outliers, and summary reporting.

The agent is built using Python and pandas, following concepts learned in the Google AI Agents Intensive course. It can be used on any tabular dataset to prepare it for analysis or machine learning tasks.

---

## Features

1. **Load CSV datasets**  
   - Automatically reads any CSV file provided.

2. **Handle missing values**  
   - Detects missing data and fills or drops it as appropriate.

3. **Remove duplicates**  
   - Automatically removes duplicate rows to maintain data integrity.

4. **Detect outliers**  
   - Identifies outliers using the IQR (Interquartile Range) method.

5. **Generate summary report**  
   - Displays a concise report showing data cleaning steps, number of missing values handled, duplicates removed, and outliers detected.

6. **Save cleaned CSV**  
   - Outputs a cleaned CSV file automatically for further use.

---

## Installation / Dependencies

- Python 3.x  
- pandas  
- numpy (optional for calculations)  
- Jupyter Notebook or Kaggle environment  

Install dependencies using pip:

```bash
pip install pandas numpy

