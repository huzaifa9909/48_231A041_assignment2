# 🧠 Sentiment Analysis on "Apple Vision Pro" Tweets

---

## 📌 Problem Statement
The goal of this project is to perform sentiment analysis on tweets related to Apple Vision Pro using machine learning techniques. The task involves classifying tweets into positive, negative, or neutral sentiments and evaluating the performance of different models.

---

## 🎯 Objective
- Perform sentiment analysis on Apple Vision Pro tweets  
- Classify tweets into Positive, Negative, and Neutral categories  
- Apply machine learning models for classification  
- Evaluate model performance using metrics  

---

## 📖 Introduction
The topic chosen for this project is Apple Vision Pro, a mixed reality headset introduced by Apple. It has gained global attention due to its advanced features and premium pricing. Public opinions vary widely, making it an ideal case for sentiment analysis.

---

## 📊 Dataset
- **Total Tweets:** 100  
- **Source:** Manually created dataset inspired by online discussions  
- **Labels:** Positive, Negative, Neutral  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted text to lowercase  
- Removed punctuation and special characters  
- Cleaned extra spaces  

### 2. Data Splitting
- **Training Data:** 80 tweets  
- **Testing Data:** 20 tweets  

### 3. Models Used
- Naïve Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  

### 4. Model Evaluation
| Model                | Accuracy | Precision | Recall |
|---------------------|----------|----------|--------|
| Naïve Bayes         | 0.75     | 0.79     | 0.69   |
| Logistic Regression | 0.60     | 0.64     | 0.51   |
| SVM                 | 0.60     | 0.64     | 0.51   |

---

## 📈 Results & Observations
- Naïve Bayes performed the best for this dataset  
- Logistic Regression and SVM showed similar performance  
- Positive sentiments were easier to classify compared to neutral and negative  
- The dataset reflects mixed reactions:
  - Excitement about innovation  
  - Concerns about high pricing  

---

## 📊 Visualizations
![Dataset](dataset.png)  
![Results](results.png)

---

## ⚠️ Limitations
- Small dataset size  
- Manually created data  
- Limited contextual understanding of language  

---

## 🤖 AI Ethics & Responsible Usage
This project was completed for academic purposes using ethically created data. No harmful or biased data sources were used.

---

## 🚀 How to Run
pip install -r requirements.txt
python main.py

---
## 📌 Conclusion

The project successfully demonstrates sentiment analysis using machine learning models. Among the models used, Naïve Bayes performed the best. The results highlight how public opinion on Apple Vision Pro is mixed, with both positive excitement and negative concerns.

---
- Name: Huzaifa Saiyad
- Roll No: 48
- UIN: 231A041
- Year: TE-AIDS
- Course: Engineering (Artificial Intelligence & Data Science)
