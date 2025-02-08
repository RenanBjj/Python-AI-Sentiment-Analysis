# 📊 Python and AI - Youtube Comments Sentiment Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![BERT](https://img.shields.io/badge/BERT-Sentiment%20Analysis-orange)](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)
[![RoBERTa](https://img.shields.io/badge/RoBERTa-Twitter%20Sentiment-brightgreen)](https://huggingface.co/cardiffnlp/twitter-xlm-roberta-base-sentiment)
[![OpenAI](https://img.shields.io/badge/OpenAI-ChatGPT-red)](https://openai.com/)

🚀 **Python AI Sentiment Analysis** is a powerful AI-driven project that extracts comments from YouTube videos and classifies their sentiment using **three different models**: BERT, RoBERTa, and OpenAI's GPT models. This allows a deeper comparison between models and provides valuable insights into audience reactions.

---

## 📌 **Key Features**

✅ **Scrapes YouTube comments via API**

✅ **Applies sentiment analysis with BERT, RoBERTa, and OpenAI GPT**

✅ **Compares results using Confusion Matrices**

✅ **Generates insightful visualizations**

---

## 🛠 **How It Works?**
The project follows this pipeline:

1️⃣ **Extract comments** from YouTube using the YouTube API.  
2️⃣ **Process comments** using Natural Language Processing (NLP).  
3️⃣ **Apply sentiment classification** using BERT, RoBERTa, and OpenAI's GPT.  
4️⃣ **Compare results** using confusion matrices and statistical analyses.  
5️⃣ **Generate visualizations** to better understand sentiment distributions.  

---

## 📂 **Project Structure**
```
📦 python_ai_sentiment_analysis
 ┣ 📜 youtube_sentiment_analysis.ipynb   # Main script
 ┣ 📜 requirements.txt                   # Project dependencies
 ┣ 📜 README.md                          # Documentation
```

---

## 🚀 **Installation & Setup**

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/RenanBjj/Python-AI-Sentiment-Analysis.git
cd Python-AI-Sentiment-Analysis
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Configure API Keys**
Create a `.env` file and add your credentials:
```env
YOUTUBE_API_KEY=your_youtube_api_key
OPENAI_API_KEY=your_openai_api_key
```

### **4️⃣ Run the Analysis**
```bash
python youtube_sentiment_analysis.py
```

---

## 📊 **Results & Insights**
### 🔹 **Sentiment Distribution**
The system generates **bar charts** displaying the distribution of sentiments across different models.

### 🔹 **Confusion Matrices**
We compare how well the models align using **heatmaps** that illustrate model agreement and divergence.

Example of Confusion Matrix for **BERT vs OpenAI**:
```python
plt.figure(figsize=(8, 6))
sns.heatmap(conf_matrix, annot=True, fmt='d', cmap="coolwarm")
plt.title("Confusion Matrix: BERT vs OpenAI Sentiments")
plt.xlabel("Sentiment OpenAI")
plt.ylabel("Sentiment BERT")
plt.show()
```

---

## 🤖 **Technologies Used**
🔹 **Python 3.8+**

🔹 **Pandas & NumPy** - Data handling and manipulation

🔹 **Matplotlib & Seaborn** - Data visualization

🔹 **Transformers (Hugging Face)** - BERT & RoBERTa models

🔹 **OpenAI API** - Sentiment classification via ChatGPT

🔹 **Google YouTube API** - Fetching YouTube comments

---

## 🤝 **Contribute**
Want to enhance this project? Here’s how you can help:

✅ **⭐ Star this repository** to show support!

✅ **💡 Open an issue** with suggestions or improvements.

✅ **📌 Submit a pull request** with new features or optimizations.

---

## 📜 **License**
This project is open-source under the **MIT License**. Feel free to use, modify, and share! 🚀

---

👨‍💻 **Developed by [Renan Marques](https://github.com/RenanBjj) - Bringing AI to Data!** 🚀

