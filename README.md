# Study_Mitra 
🎓 AI Powered Lecture Intelligence Tool

An end-to-end **AI-powered system** that converts lecture videos/audio into **structured, searchable, and intelligent learning material**. This tool automatically transcribes lectures, generates summaries, extracts key concepts, enables question answering, and supports multilingual translation — all wrapped in an easy-to-use **Gradio web interface**.

---

## 📌 Problem Statement

Students and educators often struggle with:

* Long, unstructured lecture recordings
* Difficulty revising specific topics
* Language barriers
* Time-consuming manual note-making

This project solves these problems by transforming raw lecture media into **actionable academic intelligence**.

---

## 🚀 Features

### 🔊 Lecture Transcription

* Converts **audio/video lectures** into accurate text
* Uses **Fast-Whisper** for high-speed, high-accuracy speech recognition
* Handles long lectures efficiently

### 🧠 AI-Powered Summarization

* Generates **concise lecture summaries**
* Highlights key ideas and learning objectives
* Powered by **Transformer-based NLP models**

### 🔑 Keyword & Topic Extraction

* Identifies **important concepts and keywords**
* Uses **spaCy NLP pipeline**
* Helps in fast revision and indexing

### ❓ Question Answering (Q&A)

* Ask questions directly from lecture content
* Context-aware answers generated using NLP models

### 🌍 Translation Support

* Translate lecture transcripts into multiple languages
* Helpful for multilingual learners

### 🖥️ Interactive Web Interface

* Built using **Gradio**
* Upload lecture files and get results instantly
* No backend or server configuration required

---

## 🏗️ System Architecture

```
Lecture Audio/Video
        │
        ▼
 Audio Extraction (FFmpeg)
        │
        ▼
 Speech-to-Text (Fast-Whisper)
        │
        ▼
 NLP Processing Layer
  ├─ Summarization
  ├─ Keyword Extraction
  ├─ Q&A Engine
  └─ Translation
        │
        ▼
 Gradio Web Interface
```

---

## 🛠️ Tech Stack

| Component           | Technology               |
| ------------------- | ------------------------ |
| UI                  | Gradio                   |
| Speech Recognition  | Faster-Whisper           |
| NLP Models          | HuggingFace Transformers |
| Language Processing | spaCy, NLTK              |
| Deep Learning       | PyTorch                  |
| Media Processing    | FFmpeg                   |
| Deployment          | Google Colab / Local     |

---

## 📂 Project Structure

```
AI-Powered-Lecture-Intelligence-Tool/
│
├── AI Powered Lecture Intelligence Tool.ipynb
├── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/lecture-intelligence-tool.git
cd lecture-intelligence-tool
```

### 2️⃣ Install Dependencies

```bash
pip install gradio transformers sentencepiece torch nltk spacy yt-dlp faster-whisper
python -m spacy download en_core_web_sm
```

### 3️⃣ Install FFmpeg

```bash
apt-get install -y ffmpeg
```

---

## ▶️ Running the Application

Open the notebook:

```bash
jupyter notebook "AI Powered Lecture Intelligence Tool.ipynb"
```

Run all cells and Gradio will launch a **local web interface** where you can:

* Upload lecture audio/video
* View transcript, summary, keywords
* Ask questions
* Translate content

---

## 📊 Use Cases

* 📚 Students: Smart revision & exam prep
* 👨‍🏫 Teachers: Automated lecture notes
* 🌐 E-learning platforms
* 🎧 Podcast & webinar analysis
* 🏫 EdTech startups

---

## ✅ Advantages

* Language-agnostic
* Handles long lectures
* Fully automated pipeline
* No manual note-taking
* Easy deployment

---

## ⚠️ Limitations

* Accuracy depends on audio quality
* Very long lectures may require chunking
* GPU recommended for faster processing

---

## 🔮 Future Enhancements

* Speaker diarization
* Timestamp-based navigation
* PDF / DOCX export of notes
* LMS integration
* Cloud deployment

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit changes
4. Open a Pull Request


## 👤 Author

**Manish Kumar**
**Divyanshu Rajput**
**Divyanshu Tiwari**
**Akarsh Kushwaha**
AI & ML Enthusiast | B.Tech III year stud

---

⭐ If you like this project, don’t forget to star the repository!

