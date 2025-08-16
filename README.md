# Hierarchical Multi-level Spending Classification

**SHORT INTRO**

This project aims at classifying spending categories of purchase orders using NLP techniques, one-hot enconding, and decision-treed based classifiers.
Developed a machine learning framework to classify purchase orders into spending categories across four hierarchical levels. Built multi-step models (Decision Tree, Random Forest, Gradient Boosting) integrating prior predictions, with extensive feature engineering on text (regex, TF-IDF, LSI, Word2Vec) and categorical data. Achieved strong performance at higher levels of classification, demonstrating the impact of NLP on domain-specific short-text descriptions. Designed an “Ambiguity Score” metric to communicate model limitations to non-technical stakeholders and highlighted the importance of data quality and balance in procurement ML applications.

**DATA ACCESS STATEMENT**

The data used in this report is proprietary and owned by the client. Access to the data is restricted and governed by confidentiality agreements. Redistribution or external sharing of the data is not permitted without the explicit authorization of the client. All analyses and insights presented are based on this confidential data and are intended solely for internal use.

**REQUIREMENTS**

Requirements are described in the file *requirements.txt*

**HOW TO RUN THE CODE**

Install the required dependencies listed in `requirements.txt`

1) Using **Conda** (reccomended):

   Conda Version used: 22.1.1

   Create a virtual evnvironemnt using conda

   `conda env create -f environment_setup.yml`
2) Using ***pip***

   You may want to create a virtual environment using `venv` before installing dependencies

   e.g. `python -m venv path\your_path`

   `pip install -r requirements.txt`

**SKILLS**

**Coding Language**

<div>
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python" />
</div>

**Data Manipulation**

<div>
<img src='https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white' alt='Pandas' />
</div>

**Feature Enginnering**

regex, Singular Value Decomposition, One-hot encoding, TF-IDF

**Machine Learning**

Decision Trees, Random Forest and Gradient Boosting

<img src='https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white' alt='scikit-learn' />
<img src='https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white' alt='SciPy' />


**Natural Language Processing**

<img src='https://img.shields.io/badge/NLTK-3776AB?logo=python&logoColor=fff' alt='nltk' />

gensim

**Data Visualization**

<img src='https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white&logoSize=2' alt='matplotlib' />
<img src='https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=Plotly&logoColor=white' alt='plotly' />


