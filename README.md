# CSIS 4260: Learning Web Scraping and Text Analysis  

## 📌 Overview  
This repository contains my submission for **CSIS 4260 Assignment 2**, focusing on **web scraping and text analysis**. The project is divided into two main parts:  

1️⃣ **Web Scraping** – Researching and comparing web scraping libraries, implementing a web scraper to collect at least 100 articles/pages.  
2️⃣ **Text Analysis** – Applying advanced text mining techniques to extract insights, generate summaries, and compute importance scores with direction.  

## 📂 Project Structure  
```
📦 CSIS-4260-Learning-web-scraping-and-text-analysis  
 ┣ 📜 Part-1.ipynb  ➝ Web Scraping Implementation  
 ┣ 📜 Sentiment Detection and Emotion Mining.ipynb  ➝ Text Analysis Implementation  
 ┣ 📜 Assignment 2.pdf  ➝ Official Assignment Description  
 ┗ 📜 README.md  ➝ Project Documentation (You are here)  
```

## 🚀 Part 1: Web Scraping  
### 🔹 Objective  
- Research and compare popular web scraping libraries.  
- Implement a scraper to extract **100+ articles** from a publicly available website.  
- Benchmark performance and recommend the best approach.  

### 🛠️ Technologies Used  
✅ **Libraries compared**: `BeautifulSoup`, `Scrapy`  
✅ **Final implementation**: `Scrapy`  
✅ **Data Source**: `BBC News`  

### 📊 Key Features  
✔️ Scrapes articles efficiently while handling **errors, timeouts, and delays**.  
✔️ Collects and **stores data** for further text analysis.  
✔️ Displays **final count** of articles scraped and **time taken**.  

🔗 **View Implementation:** [Part-1.ipynb](https://github.com/AshmithaJagadish/CSIS-4260-Learning-web-scraping-and-text-analysis/blob/main/Part-1.ipynb)  

---

## 📊 Part 2: Text Analysis  
### 🔹 Objective  
- Apply **at least two** text analysis algorithms on the scraped data.  
- Generate **summaries** and assign **importance scores** with sentiment direction.  
- Use **advanced NLP techniques** for deeper insights.  

### 🛠️ Techniques Used  
✅ **Summarization** – `T5 Transformer`  
✅ **Sentiment Analysis** – `Fine-Tuned BERT`  
✅ **Named Entity Recognition (NER)** – `spaCy Transformers`  
✅ **Topic Modeling** – `BERTopic with HDBSCAN & UMAP`  
✅ **Anomaly Detection** – `Autoencoder-based Model (TensorFlow)`  
✅ **Graph Neural Networks (GNNs) for Text`  
✅ **Latent Dirichlet Allocation (LDA) from Gensim`  

### 📊 Key Features  
✔️ Implements **deep learning-based sentiment analysis** with a **properly trained model**.  
✔️ Generates **comprehensive summaries** using transformers.  
✔️ Extracts **named entities and topics** for deeper insights.  
✔️ Uses **anomaly detection** to identify unusual content.  
✔️ Presents results in a **tabulated format** for better readability.  

🔗 **View Implementation:** [Sentiment Detection and Emotion Mining.ipynb](https://github.com/AshmithaJagadish/CSIS-4260-Learning-web-scraping-and-text-analysis/blob/main/Sentiment%20Detection%20and%20Emotion%20Mining.ipynb)  

---

## 💡 How to Use  
1️⃣ Clone this repository:  
   ```sh
   git clone https://github.com/AshmithaJagadish/CSIS-4260-Learning-web-scraping-and-text-analysis.git
   cd CSIS-4260-Learning-web-scraping-and-text-analysis
   ```

2️⃣ Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```

3️⃣ Run each notebook in **Google Colab** or **Jupyter Notebook**.  

---

## 🎯 Key Learnings  
🔹 **Efficiency trade-offs** in web scraping tools.  
🔹 **Advanced NLP techniques** for deep text analysis.  
🔹 **Automation** of sentiment detection & entity recognition.  
🔹 **Handling large-scale data processing** in Python.  

---

## 🏆 Acknowledgments  
Special thanks to **CSIS 4260 faculty** for providing an opportunity to explore **web scraping and NLP techniques** in-depth.  

For any questions or improvements, feel free to raise an **issue** or **pull request**! 🚀  
