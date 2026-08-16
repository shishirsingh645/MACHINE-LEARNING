# MACHINE-LEARNING

A collection of **Machine Learning, Remote Sensing, Environmental Data Analysis, and Geospatial experiments** implemented primarily as Jupyter Notebooks.

This repository contains class assignments, practical exercises, exploratory analysis, and machine-learning experiments covering **classification, regression, time-series forecasting, air-quality analysis, soil-moisture prediction, and Land Surface Temperature (LST) analysis**.

## Contents

| Notebook                                                                                         | Description                                                                                                                   |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| [`DECISSION_AND_LOGISTIC_REGRESSION.ipynb`](./DECISSION_AND_LOGISTIC_REGRESSION.ipynb)           | Classification experiments using **Decision Tree** and **Logistic Regression** methods.                                       |
| [`LST_MNDISI_BANGALORE.ipynb`](./LST_MNDISI_BANGALORE.ipynb)                                     | Analysis of **Land Surface Temperature (LST)** and remote-sensing/environmental data for Bangalore using MNDISI-related data. |
| [`MULTIPLE CLASS AQI CLASSIFICATION .ipynb`](./MULTIPLE%20CLASS%20AQI%20CLASSIFICATION%20.ipynb) | **Multi-class Air Quality Index (AQI) classification** using machine-learning techniques.                                     |
| [`SAHILSIR_LAB_ASSIGN2.ipynb`](./SAHILSIR_LAB_ASSIGN2.ipynb)                                     | Machine-learning laboratory assignment containing practical analysis and modelling exercises.                                 |
| [`SARIMAX MODEL AQI FORCASTING .ipynb`](./SARIMAX%20MODEL%20AQI%20FORCASTING%20.ipynb)           | **AQI forecasting** using the SARIMAX time-series modelling approach.                                                         |
| [`linear regression soil moisture.ipynb`](./linear%20regression%20soil%20moisture.ipynb)         | **Linear Regression** applied to soil-moisture prediction/analysis.                                                           |

## Machine Learning Topics

The repository covers several important machine-learning and statistical modelling concepts:

### Supervised Learning

* Logistic Regression
* Decision Tree Classification
* Linear Regression
* Multi-class Classification

### Time-Series Modelling

* SARIMAX
* Air-quality forecasting
* Time-dependent environmental analysis

### Environmental & Geospatial Machine Learning

* Air Quality Index (AQI) classification
* Soil-moisture modelling
* Land Surface Temperature analysis
* Remote-sensing data analysis
* Location-specific environmental modelling

## General Workflow

The notebooks generally follow a standard data-science workflow:

```text
Data Collection
      ↓
Data Loading
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Selection / Engineering
      ↓
Model Development
      ↓
Model Training
      ↓
Prediction / Forecasting
      ↓
Evaluation & Visualization
```

## Technologies

The repository is built around the Python data-science ecosystem and Jupyter Notebook environment.

Typical technologies used across the work include:

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Statistical / time-series modelling libraries
* Geospatial and remote-sensing data analysis tools

> The exact Python packages may vary between notebooks because this repository is organized as individual experiments and assignments rather than a single packaged application.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/shishirsingh645/MACHINE-LEARNING.git
cd MACHINE-LEARNING
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\activate
```

Activate it on Linux/macOS:

```bash
source .venv/bin/activate
```

### 3. Install the required libraries

Install the libraries required by the individual notebook. A typical environment may include:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

Additional packages may be required for the SARIMAX, remote-sensing, or geospatial notebooks.

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the required `.ipynb` file and execute the cells sequentially.

## Repository Structure

```text
MACHINE-LEARNING/
│
├── DECISSION_AND_LOGISTIC_REGRESSION.ipynb
├── LST_MNDISI_BANGALORE.ipynb
├── MULTIPLE CLASS AQI CLASSIFICATION .ipynb
├── SAHILSIR_LAB_ASSIGN2.ipynb
├── SARIMAX MODEL AQI FORCASTING .ipynb
├── linear regression soil moisture.ipynb
└── README.md
```

## Purpose

This repository serves as a practical learning collection for applying machine-learning and statistical methods to **real-world environmental and geospatial problems**.

The work demonstrates how machine-learning techniques can be applied to:

* Predict environmental variables
* Classify air-quality conditions
* Forecast AQI
* Analyse satellite-derived environmental information
* Model soil moisture
* Explore relationships between geographic and environmental variables

## Learning Outcomes

Working through these notebooks provides practical exposure to:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection
* Supervised machine learning
* Classification and regression
* Model evaluation
* Time-series forecasting
* Environmental data modelling
* Remote-sensing data analysis
* Visualization of analytical results

## Notes

This repository is primarily an **academic and exploratory machine-learning collection**. The notebooks may differ in structure, datasets, preprocessing methods, and modelling approaches depending on the specific assignment or experiment.

Some notebooks may require external datasets or additional Python packages that are not stored directly in the repository.

## Author

**Shishir Singh**

GitHub: [@shishirsingh645](https://github.com/shishirsingh645)

---

### Repository

[github.com/shishirsingh645/MACHINE-LEARNING](https://github.com/shishirsingh645/MACHINE-LEARNING)

