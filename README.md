# 📊 Data Science Project -- Structured & Reproducible Workflow

## 🎯 Project Philosophy

This project is not about Python skill.\
It is about professional Data Science behaviour.

The focus is on:

-   Reproducibility\
-   Clear structure\
-   Separation of exploration and outputs\
-   Writing projects others can run\
-   Reducing future mistakes (data leakage, brittle pipelines)

A strong foundation makes EDA, modelling, and deployment significantly
easier.

------------------------------------------------------------------------

## 📁 Project Structure: assignment1

├── data

├── reports

├── README.md

└── requirements.txt

------------------------------------------------------------------------

## 📂 Folder Explanation

### data/

Contains all datasets used in the project.

Internally, it follows a structured logic:
-   raw/ → immutable original data
-   interim/ → partially cleaned data
-   processed/ → cleaned & model-ready datasets

This ensures:
- Traceability
- Reproducibility
- No accidental corruption of original data

------------------------------------------------------------------------

### reports/

Contains analytical outputs such as:
-   Summary tables
-   Aggregated results
-   Final exported insights

------------------------------------------------------------------------

### requirements.txt

Lists all Python dependencies required to reproduce the project.

To install:

pip install -r requirements.txt

This guarantees environment consistency and reproducibility.

------------------------------------------------------------------------

## 🔄 Workflow

1.  Place original dataset in data/raw/
2.  Perform basic cleaning → save to data/interim/
3.  Apply feature engineering → save to data/processed/
4.  Generate analysis outputs → save to reports/

------------------------------------------------------------------------

## 🧠 Why This Structure Matters

This structure prevents:

-   Data leakage
-   Hidden preprocessing steps
-   Irreproducible experiments
-   Overwriting original datasets
-   Brittle pipelines

Professional Data Science is not about running models.
It is about building reliable systems others can trust.

---

## 👨‍💻 Author
[![LinkedIn](https://img.shields.io/badge/LinkedIn-André%20Llumiquinga-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/andre-llc/)
[![GitHub](https://img.shields.io/badge/GitHub-André%20Llumiquinga-black?style=flat&logo=github)](https://github.com/andrefernandoec2608)