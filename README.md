# 📊 Aspect-Based Sentiment Analysis on Airport Reviews  
**Sentiment Classification for Sultan Mahmud Badaruddin II Airport Using Machine Learning**

---

## ✨ Overview
This project analyzes over 1,000 user reviews from Google Maps to uncover how travelers feel about different aspects of airport service using **Aspect-Based Sentiment Analysis (ABSA)**.  
We applied three ML algorithms — **Naïve Bayes, Support Vector Machine (SVM), and Random Forest** — to classify sentiments across six key aspects.

---

## 🧠 What’s Inside?
- Web scraping reviews via **SerpAPI**
- Text preprocessing: cleaning, tokenization, normalization, stopword removal, stemming
- **Manual sentiment labeling** by 3 annotators with majority voting
- **SMOTE** for class balancing
- TF-IDF for feature extraction
- Model training with:
  - ✅ Naïve Bayes  
  - ✅ Support Vector Machine (SVM)  
  - ✅ Random Forest
- Evaluation using Accuracy, Precision, Recall, and F1-Score

---

## 📈 Key Insights
- 🏆 **Best model**: SVM with F1-score of **0.860**
- ✅ Most positive sentiment: **Airport Environment**
- ⚠️ Most negative sentiment: **Facilities**
- 📌 Real-world application of ABSA in **airport service quality improvement**

---

## 🔍 Sentiment Aspects
We analyze sentiment across 6 core aspects:
- 🛫 Check-in  
- 🔐 Security  
- 💺 Comfort  
- 🌿 Airport Environment  
- 🧼 Basic Facilities  
- 🚶 Mobility

---

### 🧠 Model Performance  
![Model Comparison](https://drive.google.com/uc?export=view&id=1xPUiMHFUa4lmiz8SLoB6pbUk7gE9ftQH)

---
## 📝 Citation

This research was published in:

> **JATI (Jurnal Mahasiswa Teknik Informatika)**, Vol. 9 No. 3, June 2025  
> Syakillah Nachwa, et al.  
> _"Pendekatan Klasifikasi dalam Knowledge Discovery untuk Analisis Sentimen Berbasis Aspek pada Ulasan Bandara Sultan Mahmud Badaruddin II di Google Maps."_  
> 📄 [Read the full publication here](https://ejournal.itn.ac.id/index.php/jati/article/view/13776)

---

## 📬 Contact  
Made with ❤️ by **Syakillah Nachwa**  
📧 syakillahnachwa081@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/chwakillah) 

---

## 🚀 Try It Yourself

```bash
# Clone the repo
git clone https://github.com/yourusername/airport-sentiment-absa.git
cd airport-sentiment-absa

# Install dependencies
pip install -r requirements.txt

# Run preprocessing
python preprocessing.py

# Train model
python train.py --model svm

# Evaluate
python evaluate.py
