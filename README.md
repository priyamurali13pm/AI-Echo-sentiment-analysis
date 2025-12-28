# 📝 AI ECHO - RoBERTa Sentiment Classification

This project is a Streamlit web app that performs sentiment analysis using a 
fine-tuned RoBERTa model. It predicts Positive, Neutral, or Negative polarity 
with high accuracy (~94%).

## 🚀 Features
- Real-time sentiment prediction
- Confidence score visualization
- Pretrained RoBERTa sentiment model
- Streamlit web interface

## 📂 Project Structure
📁 AI-Echo-sentiment-analysis
│
├── app.py # Streamlit App
├── requirements.txt # Install dependencies
├── .gitignore # Ignore unnecessary files
└── saved_roberta_model/ # (Optional) Local model storage


---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/priyamurali13pm/AI-Echo-sentiment-analysis.git
cd AI-Echo-sentiment-analysis

2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run Streamlit app
streamlit run app.py

🧠 Model Used
Model	Source
RoBERTa	cardiffnlp/twitter-roberta-base-sentiment
Framework	HuggingFace Transformers

🖥️ Demo Preview (Workflow)

User enters text in UI

RoBERTa processes input

Output class: 😡 Negative | 😐 Neutral | 😊 Positive

Confidence score shown with meter bar

📌 Future Enhancements

📎 Add CSV upload for batch prediction

📊 Add evaluation dashboard (Confusion Matrix, Accuracy, F1)

🌐 Online Deployment (Streamlit Cloud / HuggingFace Spaces)

🎙️ Voice-based sentiment input

🔗 Chat conversation memory

📌 Future Enhancements

📎 Add CSV upload for batch prediction

📊 Add evaluation dashboard (Confusion Matrix, Accuracy, F1)

🌐 Online Deployment (Streamlit Cloud / HuggingFace Spaces)

🎙️ Voice-based sentiment input

🔗 Chat conversation memory

💡 Author

Priya Murali
🖥 Data Science & NLP Enthusiast

🌟 If you like this project, give it a ⭐ on GitHub!