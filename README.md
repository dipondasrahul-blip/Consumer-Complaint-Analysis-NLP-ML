# 🧠 Consumer Complaint Analysis using NLP & Machine Learning

📅 **Period:** 2019–2024  
🧠 **Tech Stack:** Python | NLP | Machine Learning | Pandas | NLTK | Scikit-learn | Seaborn  

---

## 🎯 Objective
This project performs an end-to-end analysis of **U.S. Consumer Financial Protection Bureau (CFPB)** complaint data using **Natural Language Processing (NLP)** and **Machine Learning**.  
It identifies sentiment, complaint clusters, and potential fraud indicators from thousands of consumer narratives.

---

## 📊 Dataset Used
- **[CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)**  
  Contains millions of real consumer complaint records about financial products and institutions across the United States.

---

## 🧩 Methodology
1. **Data Preparation**
   - Cleaned and standardized complaint narratives.
   - Converted date columns into proper datetime format.
   - Sampled 20,000 rows for efficient analysis.
   
2. **Exploratory Data Analysis**
   - Identified companies and states with highest fraud-related complaints.
   - Analyzed complaint trends, response times, and disputed cases.

3. **Sentiment Analysis (VADER)**
   - Used NLTK’s VADER to categorize complaints as **Positive, Negative, or Neutral**.
   - Visualized sentiment distribution to gauge consumer satisfaction.

4. **Topic Modeling (LDA)**
   - Implemented Latent Dirichlet Allocation (LDA) to uncover hidden complaint clusters.
   - Extracted major issues such as **credit report errors**, **debt collection**, and **unauthorized charges**.

5. **Fraud Detection (Machine Learning)**
   - Labeled fraud-related texts using keyword indicators.
   - Vectorized narratives with TF-IDF and trained a **Random Forest Classifier**.
   - Achieved **98% accuracy** and **ROC-AUC = 0.995** in fraud detection.

---

## 💡 Key Insights
- **Top Fraud Companies:** Experian, Equifax, TransUnion, PayPal, Chase  
- **Fraud Hotspots:** California, Florida, Texas, New York  
- **Timely Response Rate:** 98.76% of companies responded within time  
- **Sentiment:** Over 60% of complaints expressed negative tone

---

## 📈 Dashboard & Visualization Previews

<div align="center">

### 📊 Sentiment Distribution of Consumer Complaints
<img width="100%" alt="Sentiment Distribution Chart" src="https://github.com/user-attachments/assets/7fb7f554-5297-4b4c-8921-6fb0bba7b5d2" />
*Figure 1: Overall sentiment polarity across complaint narratives.*

---

### 💬 Complaint Topic Clusters (LDA Visualization)
<img width="100%" alt="Complaint Topic Clusters" src="https://github.com/user-attachments/assets/5fd78ba8-281a-4343-8e55-54857f54d48e" />
*Figure 2: Key complaint themes extracted through topic modeling.*

---

### ⚠️ Confusion Matrix & ROC-AUC for Fraud Detection Model
<img width="100%" alt="Confusion Matrix ROC-AUC Visualization" src="https://github.com/user-attachments/assets/64eae0e2-a28b-4dd1-9f53-0e6617a1260a" />
*Figure 3: Model evaluation showing 98% accuracy and AUC = 0.995.*

</div>

---

## 🧰 Tools & Libraries
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`,  
`NLTK (VADER)`, `Gensim (LDA)`, `Scikit-learn (RandomForest)`, `PyLDAvis`

---

## 🏁 Outcome
Developed an AI-powered analytical framework to detect potential financial fraud patterns and consumer dissatisfaction trends in real time.  
Supports **regulators, policymakers, and financial institutions** in strengthening consumer protection and market transparency.

---

## 👨‍💻 Author
**Dipon Das Rahul**  
🎓 MBA in Business Analytics (STEM), Midwestern State University  
📍 Texas, USA  
📧 [dipondasrahul@gmail.com](mailto:dipondasrahul@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/diponrahul) | [GitHub](https://github.com/dipondasrahul-blip)

---

## 🧾 Tags
`#AI` `#NLP` `#MachineLearning` `#FraudDetection` `#FinancialAnalytics` `#CFPB` `#Python` `#DataScience`
