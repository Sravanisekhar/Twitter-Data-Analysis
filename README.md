# 🐦 Twitter Data Analysis

This project focuses on analyzing Twitter data to uncover **sentiments**, **clusters**, and **temporal trends** using advanced NLP and machine learning techniques.

---

## 🔍 Overview
The aim of this project is to:
- Perform **sentiment analysis** on tweets (positive, negative, neutral).  
- **Cluster similar tweets** using **TF-IDF** and **cosine similarity**.  
- Track topic evolution over time through **cluster chaining**.  
- Visualize results using **pie charts**, **word clouds**, and **emoji-based sentiment visuals**.

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Extract hashtags using regex.  
   - Tokenize and clean text using **NLTK**.  
   - Remove stopwords and unnecessary symbols.  

2. **Vectorization**  
   - Convert tweets to numerical vectors using **TF-IDF** (Term Frequency–Inverse Document Frequency).  

3. **Clustering**  
   - Apply **K-Means** and **cosine similarity** to group similar tweets.  
   - Filter clusters based on **cluster quality** and **weight**.  

4. **Cluster Chaining**  
   - Use the **Hungarian Algorithm** to connect related clusters across timestamps.  
   - Track the evolution of topics over time.  

5. **Sentiment Analysis**  
   - Classify tweets as **positive**, **negative**, or **neutral** to understand public emotion.  

6. **Visualization**  
   - Represent sentiments using **pie charts**, **word clouds**, and **emoji icons** for better interpretability.

---

## 📊 Results
- Extracted and visualized meaningful sentiment patterns.  
- Identified evolving topics across multiple timeframes.  
- Created engaging visual outputs for sentiment and cluster insights.

---

## 🚀 Future Scope
- Enable **real-time tweet analysis** for live event tracking.  
- Add **multimodal data (images/videos)** for richer social media insights.  

---

## 🧠 Tech Stack
- **Languages:** Python  
- **Libraries:** NLTK, scikit-learn, Pandas, NumPy, Matplotlib  
- **Techniques:** TF-IDF, K-Means, Cosine Similarity, Sentiment Analysis, Cluster Chaining  

