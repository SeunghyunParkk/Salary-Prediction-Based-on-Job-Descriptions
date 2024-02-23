# Salary Prediction Based on Job Descriptions

## Description

This project focuses on predicting high or low salaries from job descriptions using text analytics techniques. The objective is to build and test classification models, specifically using a Naïve Bayes classifier, to analyze how textual features extracted from job descriptions can be indicative of salary levels. The analysis includes data preprocessing, feature extraction, model training, evaluation, and exploration of methods to improve model accuracy.

## Installation

Ensure you have Python installed on your system. Then, install the required libraries using:

```bash
pip install nltk scikit-learn pandas numpy matplotlib seaborn
```
Additionally, download necessary NLTK resources:


```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
```
## Dataset Preparation
Select 2500 data points from the provided dataset, dividing them into training and test sets. Ensure the data is balanced across your target classes for more reliable model performance.

## Usage
The project involves several steps:

### Data Preprocessing: Tokenize text, remove stopwords, and apply lemmatization.
### Feature Extraction: Use CountVectorizer or TfidfVectorizer for converting text data into a vectorized format.
### Model Training: Train a Naïve Bayes classifier using the training set.
### Evaluation: Assess model accuracy and visualize results with a confusion matrix.
### Improvement: Explore strategies to enhance model performance, such as feature selection optimization and addressing class imbalance.
Refer to the Jupyter notebook for detailed code examples and methodologies.

Contributing
Contributions to improve the model or explore additional features are welcome. Please adhere to standard coding practices and document any changes.

License
Specify the license under which your project is released.
