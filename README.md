# 🎬 Gemini YouTube Video Summarizer

### 📝 Description
A Streamlit application that uses Google's Gemini 2.0 Flash model to summarize the content of YouTube videos. Just paste a video URL, click a button, and get a concise AI-generated summary powered by Gemini’s multi-modal capabilities.

## 🧠 Features

- 📺 Accepts YouTube URLs
- 🧾 Generates concise video summaries
- ⚡ Fast and interactive Streamlit UI
- 🔒 Secure API access via environment variable

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Google Generative AI (`google-generativeai`)
- dotenv

---

## 📦 Installation

**Install Dependencies**
```
pip install -r requirements.txt
```
---

## Set up environment variables

Create a .env file in the project root.
Add your Gemini API key:
```
GEMINI_API_KEY=your_api_key_here
```
---

### ▶️ Usage
Run the Streamlit app:
```
streamlit run app.py
```
Then, open your browser and go to http://localhost:8501.

Paste a YouTube video URL (e.g., https://www.youtube.com/qqqqqqqqqqqqqq) into the input box and click Summarize Video.

### 📄 License
This project is open-source under the MIT License.

### 🤝 Acknowledgments
* [Google Gemini API](https://ai.google.dev/)
* [Streamlit](https://streamlit.io/)

