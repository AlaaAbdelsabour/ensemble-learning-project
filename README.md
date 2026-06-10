# MNIST Classification using Ensemble Learning

This project is part of my learning journey from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*.

The goal of this exercise is to explore different classification models on the MNIST dataset and improve performance using Ensemble Learning techniques.

---

## 📌 Problem Statement

We aim to classify handwritten digits (0–9) using the MNIST dataset.

The dataset is split into:
- 50,000 training samples
- 10,000 validation samples
- 10,000 test samples

---

## 🧠 Models Used

The following classifiers were trained individually:

- Random Forest Classifier
- Extra Trees Classifier
- Support Vector Machine (SVM)

Then, an ensemble model was built using:

- Voting Classifier (Hard/Soft Voting)

---

## 🔗 Ensemble Learning Approach

We experimented with combining multiple models to improve performance.

Two scenarios were tested:

### 1. Voting Classifier with all models
- Includes: Random Forest, Extra Trees, SVM
- Accuracy: **0.9749**

### 2. Voting Classifier without SVM
- Models: Random Forest + Extra Trees
- Individual accuracies:
  - Random Forest: 0.968
  - Extra Trees: 0.9703
  - SVM: 0.965
- Voting Accuracy: **0.9727**

---

## 📊 Key Insight

- Ensemble models can improve or stabilize performance compared to individual classifiers.
- However, adding weaker or less aligned models does not always guarantee better results.
- Model selection inside ensembles is important.

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

---

## 🎯 What I Learned

- How to preprocess and split MNIST dataset
- Training multiple classification models
- Building ensemble models using VotingClassifier
- Comparing individual vs ensemble performance
- Understanding when ensemble improves results

---

## 📁 Project Structure
- Ensemble_Predictors.ipynb
- requirements.txt
- README.md

---

## 🚀 Future Improvements

- Try Bagging and Boosting methods (Random Forest, Gradient Boosting)
- Hyperparameter tuning
- Compare with deep learning models (Neural Networks)

---

## 👩‍💻 Author

This project is part of my Machine Learning learning journey based on:
*Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*  
