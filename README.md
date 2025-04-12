# thyroid-disease-prediction-svm-gui
A Python-based desktop app for detecting thyroid disease using SVM and PCA with a user-friendly GUI. Includes personalized medication and diet suggestions for thyroid care.
# 🩺 Thyroid Disease Prediction and Medication Suggestion System using Machine Learning (SVM)

This is a Python-based GUI application that predicts thyroid disease using Support Vector Machine (SVM) with optional PCA feature optimization. The system also provides personalized **diet, home remedies, and medication suggestions** for users at risk of thyroid disorders.

---

## 🚀 Features

- 📂 Upload and preprocess thyroid disease datasets
- 🤖 Train SVM model and improve accuracy using PCA
- 📊 Accuracy comparison graphs
- 📈 Confusion matrix visualization
- 🧾 Prediction system for new test data
- 🍎 Health suggestions, including:
  - Foods to avoid
  - Foods to eat
  - Common medications (e.g., Levothyroxine)

---

## 🛠️ Technologies Used

- Python 3
- Tkinter (GUI)
- Scikit-learn (SVM, PCA, metrics)
- Pandas, NumPy
- Matplotlib & Seaborn (visualization)

---

## 📁 How to Run the Project

1. Clone the repository:

   ```bash
    git clone https://github.com/your-username/thyroid-detection-svm.git
    cd thyroid-detection-svm
2. Install the dependencies:
    pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the application:
  Unconfirmed 172473 - Copy.py
4. Use the GUI to upload your dataset, train the model, and make predictions.
   Folder structure:
   thyroid-detection-svm/
│
 ├── Unconfirmed 172473 - Copy .py             # Main GUI application
 ├── Dataset/  hypothyroid.csv                  # Folder to place the training dataset
 ├── test/  test.csv                     # Folder to place new test datasets for prediction
 ├── README.md                   # Project overvie
5. Example Dataset Format
    Make sure your CSV contains relevant features with a final column as the target variable (e.g., disease_status).
** Note **
   This project was built for academic and educational purposes using real-world medical data for experimentation. It is not intended for professional diagnostic use.


