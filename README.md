# 🎤 Voice-Enabled AI Chatbot — Government Services

A conversational AI chatbot that understands spoken queries 
and responds with relevant government service information 
using Speech-to-Text, BERT intent recognition, 
and Text-to-Speech.

> 🎤 Speak → 🧠 AI understands → 🔊 Speaks back

---

## 🌟 What It Does

🎤 User speaks a question
↓
🔊 Speech-to-Text (SpeechRecognition)
↓
🧠 Intent Recognition (BERT — HuggingFace)
↓
💬 Response Generated
↓
🔊 Text-to-Speech (gTTS)
↓
🗄️ Logged to Firebase Firestore
---

## 💬 Example Interactions

User: "How do I apply for a passport?"
Bot:  "Visit the passport application portal
and fill out the form."
User: "I need tax information"
Bot:  "You can find tax-related information
on the revenue website."
User: "What health services are available?"
Bot:  "Contact your local health department
for services."

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| SpeechRecognition | Converting voice to text (STT) |
| gTTS | Converting text to speech (TTS) |
| HuggingFace Transformers | BERT intent recognition |
| BERT (bert-base-uncased) | NLP intent classification |
| Firebase Firestore | Cloud database for logging |
| Pandas | Data preprocessing |
| Mozilla Common Voice | Open-source audio dataset |
| Google Colab | Development environment |

---

## 📊 Dataset

**Mozilla Common Voice Delta Segment 17.0**
- Filtered for English language only
- Cleaned to remove null transcriptions
- Saved as `filtered_data.csv`

---

## 🏗️ System Components

### 1. Speech-to-Text
Converts voice input to text using 
Google Speech Recognition API

### 2. Intent Recognition
BERT model classifies query into:
- Passport Application
- Tax Inquiry
- Health Services
- Other

### 3. Text-to-Speech
gTTS converts response to audio 
and speaks it back to the user

### 4. Firebase Logging
Every query and response stored 
in Firestore for analysis

---

## 🚀 How to Run

1. Open `CA2_.ipynb` in **Google Colab**
2. Add your Firebase credentials
3. Run all cells in order
4. Speak or type your query

> ⚠️ Never push Firebase credentials to GitHub!
> Add your JSON key to .gitignore

---

## 📚 What I Learned

- Building end-to-end voice AI pipelines
- Speech-to-Text and Text-to-Speech integration
- NLP intent recognition using BERT
- Firebase Firestore database integration
- Working with real audio datasets
- Modular AI system design

---

## 👨‍💻 Author

**Srinivas Udhayasankar**
- 🌐 [Portfolio](https://srinivasudhayasankarportfolio.netlify.app)
- 💼 [LinkedIn](https://linkedin.com/in/srinivas-udhayasankar)
- 🐙 [GitHub](https://github.com/cheenusrinivas)
