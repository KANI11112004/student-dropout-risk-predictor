# 🎓 Student Dropout Risk Predictor

This is a beginner-friendly Machine Learning project to predict the **risk of student dropout** based on various academic and behavioral features. It uses a decision tree and random forest classifier to determine whether a student is at risk or not.

---

## 📁 Project Structure
```
student-dropout-risk-predictor/
│
├── data/
│   └── student-scores.csv
│
├── model/
│   ├── trained_model.pkl
│   ├── le_aspiration.pkl
│   └── le_gender.pkl
│
├── notebooks/
│   ├── data_load_clean.ipynb
│   └── prediction.ipynb
│
├── requirements.txt
├── README.md
└── LICENSE
```


---

## 📌 Highlights

- Created custom dropout risk labels using multi-factor logic
- Trained Decision Tree & Random Forest classifiers
- Achieved more accuracy with Decision Tree model
- Created interactive predictions using Jupyter Notebook

---

## 📊 Dataset

Source: Originally sourced from Kaggle
Size: 2000 student records with 17 features
Preparation: Cleaned and preprocessed manually for ML modeling

Features includes:

Attendance (absent days)
Weekly self-study hours
Academic performance (subject scores)
Part-time job status
Extracurricular activities
Career aspirations, etc.



---

## 🧠 Methodology

- Data cleaning & feature selection
- Manual label creation for dropout risk
- Label encoding for categorical values
- Model training using scikit-learn
- Accuracy evaluation with confusion matrix & classification report
- Prediction tested on custom student data

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/KANI11112004/student-dropout-risk-predictor.git
   cd student-dropout-risk-predictor
   ```
 

2. **Install the dependencies**

Make sure you have Python 3.x installed. Then install required libraries:

```bash

    pip install -r requirements.txt
```
3. **Run the Notebooks**

Open notebooks/data_load_clean.ipynb to explore the dataset, clean it, and train the model.
Open notebooks/prediction.ipynb to test the trained model on new student data.

4. **Make Predictions**
Modify the sample input in prediction.ipynb to test dropout risk prediction for any new student profile.


## 📈 Results

✅ Decision Tree Classifier: Achieved 99.5% accuracy

✅ Random Forest Classifier: Achieved 98% accuracy

🔍 Confusion Matrix & Classification Report were used to evaluate model performance

📊 Model successfully predicts dropout risk based on custom student profiles

## Acknowledgements

This was my first ML project - built with curiosity, exploration, and lots of learning. Special thanks to community platform and tools that made this beginner journey exciting.

## License

This project is licensed under the [MIT License](./LICENSE).
