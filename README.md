# Word Embedding Techniques for NLP
 Comp 545 - Natural Language Processing

## Description 
This project delves into the construction and application of two prominent word embedding models, Continuous Bag-of-Words (CBOW) and Skip-Gram, as outlined in the word2vec project. This involves the implementation of these models from scratch using PyTorch, followed by their training and evaluation on a specified dataset.

### Objectives:
* Build and understand the mechanics of the CBOW and Skip-Gram word embedding models.
* Implement preprocessing steps to convert raw text data into suitable model inputs.
* Train and optimize these models to capture semantic relationships in text.
* Analyze the models' embeddings to retrieve similar words and solve word analogies.
* Explore methods to measure and mitigate gender bias in word embeddings.

### Technologies Used:
* Programming Language: Python
* Frameworks/Libraries: PyTorch, scikit-learn
* Development Environments: Jupyter Notebook, Kaggle (for GPU acceleration)

### Features:
* Preprocessing Pipeline: Custom functions to transform text into model-ready formats, including tokenization and index conversion.
* Model Training: Techniques to train both CBOW and Skip-Gram models, including the handling of embeddings and projection layers.
* Semantic Analysis: Functions to retrieve similar words and perform word analogy tasks using the trained models.
* Bias Measurement and Mitigation: Implementation of various methods to quantify and reduce gender bias in word embeddings, such as T-SNE.

### Results for T-SNE in professions:
Max profession words: 
* 'dietitian', 
* 'housekeeper', 
* 'receptionist', 
* 'childcare worker', 
* 'paralegal', 
* 'registered nurse', 
* 'vocational nurse', 
* 'hairdresser', 
* 'dental hygienist', 
* 'salesperson'

Min profession words: 
* 'operating engineer',
* 'secretary', 
* 'conductor', 
* 'crossing guard', 
* 'director of religious activities', 
* 'mobile equipment mechanic', 
* 'lodging manager', 
* 'security system installer', 
* 'judge', 
* 'mining machine operator'

![alt text](BiasedTSNE.png?raw=true)
![alt text](DebiasedTSNE.png?raw=true)

## How to Use:
* Clone the repository to your local machine.
* Follow the installation instructions in ```requirements.txt``` to set up the environment.
* Run the script or notebook ```code.py``` to train the models and perform evaluations as documented.