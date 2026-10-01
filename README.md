# HSE-751-Reproducibility


## Purpose

This repository contains everything a data scientist needs to execute the same analytical workflow on a diabetes-centered dataset. This ensures equivalent environment, packages, software, instructions, data, and analytical findings. Follow the instructions of this file and the notebook markdown for the best results.

## Software

Google Colab

## Libraries

Python: 3.13.15 (main, Aug  6 2026, 11:06:22) [GCC 13.3.0]

pandas: 2.2.3

numpy: 2.1.3

matplotlib: 3.10.0

seaborn: 0.13.2

scipy: 1.16.3

### Install Instructions:
```bash
pip install pandas==2.2.3 numpy==2.1.3 matplotlib==3.10.0 seaborn==0.13.2 scipy==1.16.3
```

## Loading Data

In a Google Colab session, the left-side tab has a folder icon where an upload button resides to import the csv file labeled "Example Dataset_Diabetes.csv" If you decide to use another software like VS Code or a Jupyter Notebook, ensure the file names are left alone and the dataset lives in the same directory as the notebook.

## Execution

Simply run the notebook completely through without changing any code. Confirm outputs below.

## Outputs

### Step 5
Data head with first 5 rows

### Step 6
Shape: (768, 9)

Missing values:
Pregnancies       0
Glucose           0
D_BP              0
Skin_Thickness    0
Insulin           0
BMI               0
Pedigree          0
Age               0
Outcome           0
dtype: int64

Data types:
Pregnancies         int64
Glucose             int64
D_BP                int64
Skin_Thickness      int64
Insulin             int64
BMI               float64
Pedigree          float64
Age                 int64
Outcome             int64
dtype: object

Dataset shape is correct.

### Step 7 
Summary table with averages, medians, variations, quartiles, and ranges of all 9 variables.
    
### Step 8 
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/107cebf0-82ba-4d8c-8087-edcb38c16da9" />
<img width="577" height="455" alt="image" src="https://github.com/user-attachments/assets/b83905e3-8312-461a-87f7-713360d4a544" />
<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/f08ef484-7c48-4bf8-8c26-d1d6364068e7" />
<img width="578" height="445" alt="image" src="https://github.com/user-attachments/assets/c88896be-f173-439c-8a56-3bebbf5fa98e" />

### Step 9 
<img width="772" height="926" alt="image" src="https://github.com/user-attachments/assets/1d07b0fd-ae39-4bac-a7e2-52df0588d4ab" />

### Step 10 
t-statistic: -14.600060005973894
p-value: 8.935431645289912e-43

F-statistic: 28.69642914390531
P-value: 9.60848982588671e-13

### Step 12
A small table of random 8 samples

Bootstrap mean BMI: 31.789322916666666


## Limitations
This analysis is preliminary and should not be used to make concrete conclusions about the eight variables and the diabetes target. The dataset is also small (under 1000) patients, therefore, if being used for machine learning models, overfitting and limited representation are possible.
