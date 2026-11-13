# DSCI 552 Homework 7

Multi-class and multi-label classification with support vector machines, k-means clustering on the UCI Anuran Calls (MFCCs) data set, and ISLR exercises.

## Structure

```text
.
├── Homework 7 Data/
│   ├── Frogs_MFCCs.csv
│   └── Readme.txt
├── notebook/
│   └── Agudanmu_Danmu.ipynb
└── README.md
```

## How to run

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn imbalanced-learn jupyter
cd notebook
jupyter notebook Agudanmu_Danmu.ipynb
```

The notebook reads the CSV file from `../Homework 7 Data/`, so run it from the `notebook/` folder. Run all cells to generate the plots, cross-validation results, and clustering summaries. The original data files are not modified.
