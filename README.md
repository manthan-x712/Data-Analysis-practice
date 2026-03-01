# Data Cleaning & Preprocessing (Titanic Dataset)

## What This Experiment Does
- Loads the Titanic dataset (`titanic.csv`)
- Handles missing values (Age, Cabin, Embarked)
- Removes duplicate rows
- Encodes categorical columns (Sex, Embarked)
- Scales numerical columns (Age, Fare) using StandardScaler

---

## Requirements

Install the required libraries before running:

```bash
pip install pandas numpy scikit-learn jupyter
```

---

## How to Run in Jupyter Notebook

### Step 1 – Set Up Your Folder

Make sure both files are in the **same folder**:
```
your-folder/
├── titanic.csv
└── your_notebook.ipynb   ← (the notebook you create)
```

### Step 2 – Launch Jupyter Notebook

Open your terminal/command prompt, navigate to that folder, and run:

```bash
jupyter notebook
```

Then create a new notebook: click **New → Python 3**

---

### Step 3 – Copy & Paste the Code

Create a new cell for each block below and run them one by one (Shift + Enter).


## Expected Output Summary

| Column | After Processing |
|---|---|
| Age | Mean-filled, then standardized |
| Fare | Standardized |
| Sex | Encoded: female=0, male=1 |
| Embarked | One-hot encoded into 3 columns |
| Cabin, Name, Ticket | Dropped |

---
