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

  ## 🔮 Future Work
This prototype can be expanded and improved in several ways:

1. **Fairness & Bias Detection**  
   - Integrate fairness metrics to check if the model disproportionately rejects resumes based on gendered words, education background, or other sensitive attributes.  
   - Add explainable AI (XAI) techniques to make predictions transparent.

2. **Larger Dataset**  
   - Train on hundreds or thousands of resumes to improve generalization.  
   - Use open datasets or anonymized resumes to build a more robust model.

3. **Deployment**  
   - Convert the notebook into a web app using Flask/Django.  
   - Allow recruiters to upload resumes and get instant predictions.  
   - Add a dashboard with visualizations (accuracy charts, fairness metrics).

4. **Advanced NLP**  
   - Move beyond keyword frequency to embeddings (Word2Vec, BERT).  
   - Capture semantic meaning of resumes for smarter classification.

5. **Integration**  
   - Connect with LinkedIn or job portals for real‑world testing.  
   - Explore multilingual resume screening for global recruitment.


## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/AI-Resume-Screener.git


<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/22e5949c-8f80-4036-90d0-1598c058cf58" />
<img width="567" height="435" alt="image" src="https://github.com/user-attachments/assets/7658d029-5f91-44b4-bbef-a816c4c51da3" />

