# COMP1891 - Data Fundamentals

## Tutorial 01 | Spring 2026 | University of Greenwich

---

## 📌 Overview

This repository contains materials for **Week 1 Tutorial** of COMP1891 - Applications of AI and Data Science. The tutorial recaps foundational concepts in Python.

## 📁 Project Structure

**Below is a basic structure of a data project, you can create it in the upcoing tutorials**

```
UoG-COMP1891-SP26-Tutorial01/
│
├── data/
│   ├── raw/              # Original, immutable data
│   └── processed/        # Cleaned, transformed data
│
├── notebooks/            # Jupyter notebooks for exploration and analysis
│
├── src/
│   ├── utils/            # Helper functions and utilities
│   └── analysis/         # Analysis scripts
│
├── outputs/
│   ├── figures/          # Generated graphics and plots
│   └── reports/          # Analysis reports
│
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── .gitignore            # Git ignore file
```

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd UoG-COMP1891-SP26-Tutorial01
```

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
# or
venv\Scripts\activate     # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 📦 Required Libraries

| Library                | Purpose                          |
| ---------------------- | -------------------------------- |
| **pandas**       | Data manipulation and analysis   |
| **numpy**        | Numerical computing              |
| **matplotlib**   | Basic plotting and visualization |
| **seaborn**      | Statistical data visualization   |
| **jupyter**      | Interactive notebook environment |
| **scipy**        | Scientific computing             |
| **scikit-learn** | Machine learning tools           |

## 🚀 Getting Started

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Quick Start with Python

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load data
df = pd.read_csv('data/raw/your_data.csv')

# Basic exploration
print(df.head())
print(df.info())
print(df.describe())
```

## 📊 Tutorial Topics

- Introduction to Python for Data Analysis
- Data Types and Structures
- Loading and Inspecting Data
- Basic Data Manipulation with Pandas
- Introduction to Data Visualization

## 📝 Notes

- Place raw data files in `data/raw/` directory
- Save processed data to `data/processed/` directory
- Use notebooks for exploratory analysis
- Save final figures to `outputs/figures/`

## 🔗 Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)

## 📄 License

This project is for educational purposes as part of the COMP1891 course at the University of Greenwich.

---

*Last Updated: January 2026*
