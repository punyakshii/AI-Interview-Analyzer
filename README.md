# AI Interview Analyzer using NLP and Transformers

An AI-powered Interview Analysis System built using NLP, Transformers, and Speech Recognition.

This project simulates a real interview environment where users can answer interview questions through text or speech, and the system evaluates communication quality, confidence, grammar, and technical knowledge.

---

# Features

## Resume Analysis
- Resume PDF upload
- Skill extraction from resume

## AI Interview Questions
- AI-generated interview questions
- Multiple interview rounds

## Answer Input Methods
- Text-based answers
- Speech-based answers
- Speech-to-text conversion

## NLP Analysis
- Sentiment Analysis
- Grammar Error Detection
- Grammar Suggestions
- Technical Keyword Detection
- Confidence Analysis
- Communication Scoring
- Filler Word Detection

## Final Evaluation
- Interview performance report
- Improvement suggestions
- Communication feedback
- Technical assessment

---

# Technologies Used

- Python
- NLP
- Transformers
- Hugging Face
- SpeechRecognition
- PyPDF2
- LanguageTool
- Google Colab

---

# Project Workflow

```text
Resume Upload
      ↓
Skill Extraction
      ↓
AI Question Generation
      ↓
Text/Speech Answers
      ↓
Speech-to-Text
      ↓
NLP Analysis
      ↓
Final Interview Report
```

---

# Installation

Install required libraries:

```bash
pip install -r requirements.txt
```

---

# Run the Project

Open the notebook:

```bash
AI_Interview_Analyzer.ipynb
```

Run all cells in Google Colab.

---

# Project Features in Detail

## Grammar Analysis
Detects:
- grammar mistakes
- incorrect sentence structure
- writing issues

Provides:
- explanations
- correction suggestions

---

## Confidence Analysis
Detects confident words such as:
- implemented
- developed
- designed
- optimized

Generates confidence score.

---

## Communication Analysis
Evaluates:
- answer clarity
- positivity
- filler words
- technical explanations
- answer length

---

## Speech Recognition
Users can:
- upload WAV audio
- convert speech to text
- analyze spoken interview responses

---

# Example Output

```text
QUESTION:
Explain your NLP project.

GRAMMAR ANALYSIS
Mistake:
"I has developed NLP project."

Suggestion:
"I have developed NLP project."

TECHNICAL ANALYSIS
Detected Keywords:
['python', 'nlp']

COMMUNICATION SCORE:
8.4 / 10

IMPROVEMENT SUGGESTIONS:
- Improve grammar accuracy
- Add more project impact details
```

---

# Future Improvements

- Streamlit Web App
- Real-time microphone support
- Resume-job matching
- AI-generated HR feedback
- PDF interview report
- Video interview analysis

---

# Repository Structure

```text
AI-Interview-Analyzer/
│
├── AI_Interview_Analyzer.ipynb
├── README.md
├── requirements.txt
├── sample_resume.pdf
├── sample_audio.wav
└── screenshots/
```

---

# Author

Punyakshi Solanki

---

# GitHub Topics

```text
nlp
transformers
python
speech-recognition
machine-learning
interview-analyzer
huggingface
ai
```
