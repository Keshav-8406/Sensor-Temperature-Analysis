# 🌡️ Sensor Temperature Analysis

A simple Python project to analyze daily temperature readings from 4 weather stations using **NumPy**.

## 📊 Overview

- Each station has 5 daily readings.  
- The project performs three main tasks:
  1. Finds the shape of the data and computes the **average temperature per station**.  
  2. Extracts all **temperatures above 28°C**.  
  3. **Normalizes** all temperatures to a **0–1 range**.

## ⚡ Key Features

- Uses **NumPy arrays** for efficient computation.  
- Applies boolean masks to filter data.  
- Normalizes and rounds values for easy interpretation.  
- Outputs are printed directly in the notebook.

## 📝 How to Use

1. Open the notebook `Keshav_Kaushik_Assignment.ipynb` in **Google Colab**.  
2. Run all cells step by step.  
3. View all outputs below each cell.

## 🔹 Sample Outputs

**Data Shape:** `(4, 5)`  
**Mean per Station:** `[25.3, 23.78, 26.58, 25.26]`  
**Temperatures > 28°C:** `[31.2, 28.7, 30.5, 33.1, 29.6, 31.9, 28.1]`  
**Normalized Data:** 
```
[[0.33 0.11 0.88 0.72 0.49]
[0. 0.35 0.84 0.58 0.29]
[1. 0.78 0.07 0.42 0.66]
[0.18 0.39 0.92 0.68 0.34]]
```

---

## ⚠️ Important Notes :-  
- Only **NumPy** is required.  
- Notebook is ready for submission with all outputs visible.
- All steps follow the assignment instructions.
