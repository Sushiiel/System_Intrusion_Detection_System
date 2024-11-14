# System Intrusion Detection System - Exploratory Data Analysis (EDA) and Modeling

This repository contains an Exploratory Data Analysis (EDA) and initial modeling attempts for the "System Intrusion Detection System" project. The objective is to analyze and model the KDD 2020 dataset, which consists of system files data, to detect potential intrusions effectively.

## Project Structure

- **System_intrusion_detection_system.ipynb**: The Jupyter notebook that includes the EDA, initial modeling attempts, and findings.
- **README.md**: Project overview and instructions for running the analysis.
- **data/**: (Optional) Directory to store raw or processed data files used in this project.
- **images/**: (Optional) Directory for saving figures or charts generated during the analysis.

## Key Objectives

1. **Data Understanding**: Explore and understand the structure of the KDD 2020 dataset, focusing on system files data related to potential intrusions.
2. **Data Cleaning**: Handle missing values, outliers, and inconsistencies to prepare the dataset for effective modeling.
3. **Exploratory Data Analysis**: Perform univariate, bivariate, and multivariate analyses to uncover patterns and relationships indicative of system intrusions.
4. **Initial Modeling**: Test both LSTM and traditional supervised learning models to find the best approach for this dataset.

## Modeling Approaches

### LSTM Attempt
Initially, an LSTM (Long Short-Term Memory) model was used to capture temporal patterns in the system data. However, due to low accuracy with the complex structure of the system files, this model was found unsuitable for the task.

### Supervised Models
After the LSTM model's low performance, the approach was shifted to traditional supervised learning models. These models, such as classifiers, provided higher accuracy and were more suitable for identifying system intrusions.

## Getting Started

### Prerequisites

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` (for supervised modeling)

### Running the Analysis

1. Clone this repository:
   ```bash
   git clone https://github.com/Sushiiel/System_Intrusion_Detection_System.git
