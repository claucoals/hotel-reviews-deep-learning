# Hotel Reviews Deep Learning

## Description  
This repository contains the solution to the **Machine Learning, Artificial Neural Networks and Deep Learning exam** (Exam session: 19 June 2025, University of Pavia, University of Milan "La Statale" and University of Milano-Bicocca).  
The task consists of designing and implementing a **deep neural network** able to predict both the **review type** (good/bad) and the **review score** (0–10) from hotel reviews.  

## Contents  
- `carboni_535421_dl_exam.ipynb`: Jupyter Notebook implementing preprocessing, model design, training, and evaluation.  
- `input_data.csv`: Dataset with hotel reviews, metadata, and labels for training/testing.  

## Approach  
- **Model**: Deep neural network tailored for text classification and regression.  
- **Input**: Preprocessed reviews (tokenization, embeddings) with structured metadata.  
- **Output**: Review type (binary classification) and/or review score (regression).  
- **Loss**: Cross-entropy for classification, MSE for regression.  
- **Evaluation**: Accuracy/F1 for classification, RMSE for regression.  

## Requirements  
```bash
pip install numpy pandas tensorflow scikit-learn matplotlib
```  

## Usage  
Clone the repository and run the notebook:  
```bash
git clone https://github.com/your-username/hotel-reviews-deep-learning.git
cd hotel-reviews-deep-learning
jupyter notebook carboni_535421_dl_exam.ipynb
```  

---

## License  
For educational use only — part of the academic coursework at university.  
