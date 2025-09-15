# Python Student Competence Analysis

## Overview
This project evaluates Python student code submissions and generates detailed analysis including:
- Summary of what the code does
- Core computer science concepts involved
- Likely misconceptions or reasoning gaps
- Single-sentence hints for improvement
- Competence scores with justification

The main goal is to assess student understanding in Python programming and provide meaningful feedback.

## Model
The analysis uses the **StarCoder2-3B** model from Hugging Face, which is a large open-source code model suitable for evaluating code comprehension.

## Files in the Repository
- `colab_notebook.ipynb` – Google Colab notebook that runs the analysis on multiple student codes and generates the CSV.  
- `student_analysis.csv` – Output CSV with analysis for each student code snippet.  
- `README.md` – This file explaining the project and usage.

## How to Run
1. Open `colab_notebook.ipynb` in [Google Colab](https://colab.research.google.com/).  
2. Make sure you have the required libraries installed (already included in Colab usually):
```bash
pip install transformers pandas