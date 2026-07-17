# Neurofive ML Track

My learning journey through the Neurofive Solutions AI/ML internship track — hands-on tasks in data analysis, machine learning, and model building.

## Week 1 — Task 1: Titanic Dataset EDA

**Goal:** Set up the Python toolkit and perform first Exploratory Data Analysis (EDA) — understanding a dataset's shape, quality, and quirks before modeling anything.

### Setup
- Python 3, Jupyter Notebook
- Libraries: `pandas`, `numpy`

### Dataset
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) (Kaggle)

### What I did
- Loaded the dataset with `pandas.read_csv()`
- Inspected structure with `.info()`, `.describe()`, and `.head()`
- Identified missing values and their percentage per column
- Split columns into numerical vs categorical

### Key findings
- **891 rows, 12 columns** — one row per passenger
- **Cabin**: 687 missing (77.1%) — most passengers have no cabin recorded
- **Age**: 177 missing (19.87%) — will need imputation before modeling
- **Embarked**: 2 missing (0.22%) — negligible
- Numerical columns: `PassengerId`, `Survived`, `Pclass`, `Age`, `SibSp`, `Parch`, `Fare`
- Categorical columns: `Name`, `Sex`, `Ticket`, `Cabin`, `Embarked`
- `Survived` and `Pclass` are stored as `int64` but are actually categorical/ordinal — important to remember for future modeling

### Files
- `neurofive-ml-track.ipynb` — the EDA notebook

---

*More tasks will be added here as the track progresses.*
