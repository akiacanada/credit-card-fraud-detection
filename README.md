# Credit Card Fraud Detection: A Decade in Comparison (2013 vs 2023) (R)

## Overview

This project uses RMarkdown to investigate the evolution of credit card fraud over a decade by comparing two 
datasets from 2013 and 2023. I developed, evaluated, and compared four machine 
learning models—Logistic Regression, Decision Tree, Neural Network, and XGBoost—to 
classify fraudulent transactions and explore how fraud patterns have changed over time.

## Objectives

- Compare model performance on fraud data from two different eras

- Understand how fraud characteristics have evolved

- Evaluate the effectiveness of traditional vs. modern ML approaches

- Handle class imbalance and implement robust evaluation strategies


## Models Used

- Logistic Regression

- Decision Tree Classifier

- Neural Network (Keras Sequential)

- XGBoost Classifier


## Tools & Libraries

- R
- RMarkdown
- tidyr
- treemapify
- scales
- stringr
- data.table
- dplyr
- ggplot2
- corrplot
- caret
- ROCR
- rpart
- nnet
- xgboost
- DMwR2
- e1071
- pROC



## Installation

To install the required packages, run the following R code:

'''R
install.packages(c("tidyr", "treemapify", "scales", "stringr", "data.table", "dplyr", 
                   "ggplot2", "corrplot", "caret", "ROCR", "rpart", "nnet", "xgboost", 
                   "DMwR2", "e1071", "pROC"))

If you prefer, you can also create a **requirements.R** file in your repo with this content:

'''R
required_packages <- c("tidyr", "treemapify", "scales", "stringr", "data.table", "dplyr",
                       "ggplot2", "corrplot", "caret", "ROCR", "rpart", "nnet", "xgboost",
                       "DMwR2", "e1071", "pROC")

install.packages(required_packages)

## Installation

Run 'requirements.R' to install all necessary packages:

'''R
source("requirements.R")


---

  
## Key Results


- XGBoost consistently outperformed other models in both years, with a precision-recall 
trade-off best suited for high-stakes fraud detection.

- The 2023 dataset showed a greater sophistication in fraud patterns, reducing 
effectiveness of simpler models.

- Significant drift observed in feature importance and model calibration.

## Getting Started

1. Clone the repository:
  git clone https://github.com/yourusername/credit-card-fraud-detection.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
  jupyter notebook

4. Open 'credit_card_fraud_detection.ipynb' and follow the cells.

## Results

Achieved high precision and recall using XGBoost, making the model highly effective at identifying fraudulent transactions.

## License

This project is open source and available under the MIT License.
 
