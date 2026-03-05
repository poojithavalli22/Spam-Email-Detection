# Spam Email Detection using Machine Learning

## Overview
This project implements a Spam Email Detection system using Python and Machine Learning.  
The model analyzes email messages and classifies them as **Spam** or **Not Spam** based on patterns learned from a dataset.

The system uses the **Naive Bayes algorithm** for classification and evaluates the model using accuracy.

---

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Machine Learning  

---

## Dataset
The project uses the **SMS Spam Collection Dataset** which contains labeled messages.

Example format:

| Label | Message |
|------|--------|
| ham | Hi, how are you |
| spam | Congratulations! You won a prize |

---

## Project Workflow
1. Load dataset using Pandas  
2. Perform data preprocessing and label conversion  
3. Convert text messages into numerical features  
4. Train the model using Naive Bayes algorithm  
5. Evaluate the model using accuracy  
6. Predict whether a message is spam or not  

---
