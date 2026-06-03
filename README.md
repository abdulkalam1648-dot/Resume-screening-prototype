# Resume-screening-prototype
Prototype ML model for resume classification
# AI-Powered Resume Screener (Prototype)

## 📌 Overview
This project is a prototype machine learning model that classifies resumes into **“shortlist”** vs **“reject”** using keyword frequency and basic NLP techniques.  
It demonstrates how AI can be applied to recruitment while highlighting the importance of fairness and ethics in automated decision-making.

## 🎯 Why Future-Proof?
Ethical AI in recruitment will remain a global hot topic.  
This prototype can later evolve into a **fairness-aware system** that checks for bias and ensures transparent hiring practices.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Scikit-learn
- NLTK
- Matplotlib (for visualization)

## ⚙️ How It Works
1. **Dataset**: A CSV file of resumes with labels (`shortlist` / `reject`).
2. **Preprocessing**: TF-IDF vectorization for smarter keyword weighting.
3. **Models Tested**:
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)
4. **Evaluation**: Precision, recall, F1-score, and accuracy comparison.
5. **Prediction**: Test new resumes by entering text and checking classification.

## 📊 Results
- Logistic Regression: Baseline model
- Random Forest: Stronger performance on small datasets
- SVM: High precision with linear kernel
- Accuracy comparison visualized with bar charts

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/AI-Resume-Screener.git
