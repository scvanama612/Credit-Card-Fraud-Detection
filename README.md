 Credit Card Fraud Detection 🕵️‍♂️💳

This is a personal project I worked on to detect fraudulent transactions using real-world credit card data. The dataset was very imbalanced (most transactions are not fraud), so my focus was on model accuracy and recall for the minority (fraud) class.

## 🔍 What I Did

- **Cleaned and explored the dataset** using Pandas and Seaborn
- **Handled class imbalance** using under-sampling and SMOTE
- **Trained multiple models** (Logistic Regression, Random Forest, and a Neural Network using TensorFlow)
- **Evaluated results** using confusion matrix, precision, recall, F1-score, ROC-AUC
- **Saved the final model** using Keras `.h5` format

## 📁 File Structure

.
├── data/ # contains creditcard.csv
├── models/ # saved trained model (.h5 file)
├── fraud_detection.ipynb # full notebook with code, charts, and model results
└── README.md # this file

python
Copy
Edit

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Highlights

- Achieved ~99.8% overall accuracy
- Focused on detecting frauds (high precision & recall for fraud class)
- Learned how to work with imbalanced data and evaluate properly
- All the work was done locally using Jupyter Notebook

## 🤝 Why I Built This

I wanted to challenge myself with a realistic dataset and practice everything I know in one place: data cleaning, modeling, evaluation, and saving a model. This was a solo project where I did everything from scratch without using any templates.

## 🔗 Contact

 [LinkedIn](https://www.linkedin.com/in/saichandravanama).
