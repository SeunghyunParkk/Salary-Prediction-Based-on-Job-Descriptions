# Salary Prediction Using Job Descriptions

## Overview
This project focuses on utilizing text analytics to predict salary categories ('high' or 'low') based on job descriptions. Using machine learning models and natural language processing (NLP) techniques, we analyze key features in job postings to identify patterns associated with salary levels. The project achieves a model accuracy of **79.2%**, demonstrating the potential of text-based classification in real-world applications.

---

## Key Findings

### Model Performance
- **Accuracy**: 79.2%
- **Confusion Matrix Analysis**:
  - **High Salary**: 
    - Precision: 52.87%
    - Recall: 73.45%
  - **Low Salary**: 
    - Precision: 80.88%
    - Recall: 91.25%

### Significant Words
- **Top 10 Words Indicative of High Salary**:
  1. Architect (20.3x more likely)
  2. Allegis (15.4x more likely)
  3. Collaborative (8.8x more likely)
  4. Scrum (8.5x more likely)
  5. Instrumentation (8.0x more likely)
  6. Transformation (7.9x more likely)
  7. ACA (7.4x more likely)
  8. Equity (6.9x more likely)
  9. Cloud (6.8x more likely)
  10. Analogue (5.8x more likely)

- **Top 10 Words Indicative of Low Salary**:
  1. Restaurant (13.5x more likely)
  2. Repair (11.2x more likely)
  3. We (10.5x more likely)
  4. Teacher (9.2x more likely)
  5. NMC (9.0x more likely)
  6. Assistant (8.8x more likely)
  7. Hospitality (8.6x more likely)
  8. Invoice (8.3x more likely)
  9. School (8.3x more likely)
  10. Kitchen (7.9x more likely)

---

## Methods and Techniques

### Data Preprocessing
- Tokenization and lemmatization of job descriptions.
- Feature selection using the 2000 most frequent words.

### Model Improvements
1. **Addressing Class Imbalance**:
   - The dataset showed significant imbalance between high and low salary classes, negatively impacting the model's performance.
   - Techniques like resampling or weighted loss functions were considered.

2. **Feature Optimization**:
   - Increasing the number of features (words) to provide more comprehensive information for classification.

3. **TF-IDF Transformation**:
   - Applied TF-IDF to highlight words that are particularly relevant to the classification task, improving model accuracy.

---

## Future Work
- Experiment with advanced models like transformers for text classification.
- Collect additional data to mitigate class imbalance.
- Explore more sophisticated feature engineering techniques.

---

## Data Source
The dataset for this project was obtained from the Kaggle competition: [Job Salary Prediction](https://www.kaggle.com/competitions/job-salary-prediction/).

---


## Author

**Seunghyun Park**
