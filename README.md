# Phising Link Detection

## **Description**
This project aims to combat the rising tide of cybercrimes in the era of rapidly advancing technology, specifically targeting the propagation of harmful phishing links that pose serious threats due to data breaches. By harnessing predictive techniques, the goal is to proactively mitigate the impact of deceptive links. In anticipation of phishing attempts, this initiative seeks to detect and neutralize potentially harmful URLs, contributing to a safer digital landscape. 
The project draws its dataset from https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls, encompassing a collection of URLs labeled as "good" and "bad". Leveraging data preprocessing, the project extracts valuable features including domain, subdomain, suffix, path, and parameters, essential for informed predictions. Employing a robust array of models such as XGBoost, Random Forest, Gradient Boosting Classifier, Neural Networks, Logistic Regression, and linear SVC, this endeavor aspires to proactively safeguard users from malicious online activities.

## **Project Code:**
Steps:
1. Define Problem
2. Installing needed Libraries
3. Data Collection
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Data Preprocessing
   - Data Splitting
   - Random Undersampling
   - URL Extraction
   - Convert Dictionary to Dataframe
7. Feature Engineering
    - n-gram
    - Label Encoding
    - Convert Data to a list
    - One Hot Encoding
    - Sparse matrix conversion
8. Moddeling
    - XGBoost
    - Random Forest
    - Gradient Boosting Classifier
    - Neural Networks
    - Logistic Regression
    - Linear SVC
9. Measure accuracy of models
10. Conclusion
s
## **Installation**
1. Clone the repository: `git clone https://github.com/Lexuz17/Phising_Link_Detection.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## **Results and Findings**

In this project, several crucial findings and results have been obtained:
1. **Imbalanced Exploratory Data Analysis (EDA):** During the EDA phase, it's regrettable that the utilized data is imbalanced, with the "good" label data being more prevalent, approximately twice as much as the "bad" label data. This imbalance potentially leads to the loss of important information. To address this, undersampling was implemented to ensure balanced data, although there's a trade-off with the risk of losing valuable insights.
2. **Performance of XGBoost and Neural Networks Models:** In the model evaluation, it's evident that both the XGBoost and Neural Networks models yield satisfying accuracy results, achieving an impressive 93%. Furthermore, the precision, recall, and F1-score of these models also demonstrate balanced outcomes. These findings indicate that both models are proficient in classification, striking a balance between precision and recall.
These results collectively underscore that the XGBoost and Neural Networks models have the potential for real-world applications in identifying harmful links. The high accuracy and balanced evaluation outcomes hold the promise of assisting individuals in avoiding potentially hazardous links.

## Contact
For any questions or inquiries, please contact jason.susanto1703@gmail.com
