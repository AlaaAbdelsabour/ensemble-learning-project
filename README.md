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
- MLPClassifier

Then, an ensemble model was built using:

- Voting Classifier (Hard/Soft Voting)

---

## 📊 Results & Ensemble Comparison

We evaluated different ensemble configurations using Voting Classifier:

### 🟦 1. Voting Classifier (All Models)
- Models included: Random Forest, Extra Trees, SVM, MLPClassifier.
  
**Individual Model Performance:**
- Random Forest: 0.9736
- Extra Trees: 0.9743
- SVM: 0.8881
- MLPClassifier: 0.966

**Ensemble Accuracy:**
- Accuracy: **0.9749**

---

### 🟩 2. Voting Classifier (Without SVM)
- Models included: Random Forest, Extra Trees,MLPClassifier.

**Ensemble Accuracy:**
- Voting Classifier: **0.9769**

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
