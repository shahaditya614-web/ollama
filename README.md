# 📝 Offline Grammar Corrector using Ollama & Gemma 3

An AI-powered **offline grammar correction assistant** built with **Python**, **Ollama**, and **Gemma 3**. This project automatically detects grammar, spelling, and punctuation mistakes, provides corrected sentences, and explains each mistake in simple language.

The application works completely **offline** using a locally running Large Language Model (LLM), making it fast, private, and suitable for educational use.

---

# 📖 Project Overview

This project uses the **Gemma 3** language model through **Ollama** to perform English grammar correction.

The assistant:

- Corrects grammar mistakes
- Fixes spelling errors
- Corrects punctuation
- Explains grammar mistakes
- Returns structured JSON output
- Runs completely offline

This project is ideal for students learning English grammar and developers exploring Local LLM applications.

---

# ✨ Features

- ✅ Offline AI Grammar Correction
- ✅ English Grammar Checking
- ✅ Spelling Correction
- ✅ Punctuation Correction
- ✅ Grammar Explanation
- ✅ JSON Response Format
- ✅ Interactive Command-Line Interface
- ✅ Local LLM using Ollama
- ✅ Beginner-Friendly Python Code

---

# 🛠 Technologies Used

- Python
- Ollama
- Gemma 3
- JSON
- Command Line Interface (CLI)

---

# 📂 Repository Structure

```
Offline-Grammar-Corrector/
│
├── grammer.py
└── README.md
```

---

# 🔄 Workflow

```
User Input
      │
      ▼
Python Application
      │
      ▼
Ollama
      │
      ▼
Gemma 3 Model
      │
      ▼
Grammar Analysis
      │
      ▼
JSON Response
      │
      ▼
Corrected Sentence
+
Grammar Explanation
```

---

# 📦 Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/Offline-Grammar-Corrector.git
```

Navigate to the project folder

```bash
cd Offline-Grammar-Corrector
```

Install Ollama Python package

```bash
pip install ollama
```

---

# ⚙️ Install Ollama

Download and install Ollama for your operating system.

After installation, pull the Gemma 3 model:

```bash
ollama pull gemma3:4b
```

Start the Ollama server if it is not already running.

---

# ▶️ Running the Project

Run the application:

```bash
python grammer.py
```

---

# 💻 Example

### Input

```
He go to school everyday
```

### Output

```
Corrected Sentence

He goes to school every day.

Mistakes Found

1.

Wrong:
go

Fix:
goes

Reason:
The subject "He" is singular, so the verb must be "goes".

2.

Wrong:
everyday

Fix:
every day

Reason:
"Every day" refers to something happening daily, while "everyday" is an adjective.

3.

Wrong:
Missing period

Fix:
.

Reason:
Every sentence should end with proper punctuation.
```

---

# 📚 Learning Outcomes

This project demonstrates:

- Large Language Models (LLMs)
- Local AI Applications
- Ollama Integration
- Prompt Engineering
- JSON Output Generation
- Grammar Correction
- Python Programming
- AI-based Text Processing
- Command-Line Application Development

---

# 🎯 Applications

- English Learning
- Grammar Checking
- Writing Assistance
- Student Projects
- AI Education
- Offline AI Applications
- Local Language Models
- Prompt Engineering Practice

---

# 🚀 Future Improvements

- GUI using Tkinter
- Streamlit Web Application
- Gradio Interface
- PDF Grammar Correction
- DOCX Grammar Correction
- Multiple Language Support
- Grammar Score
- Writing Suggestions
- Voice Input
- REST API using FastAPI

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project is developed for educational and learning purposes.

---

# 👨‍💻 Author

## Aditya Shah

**B.Tech Information Technology Student**

### Areas of Interest

- Artificial Intelligence
- Generative AI
- Large Language Models (LLMs)
- Natural Language Processing (NLP)
- Python Development
- Machine Learning

---

⭐ If you found this project useful, please consider giving the repository a **Star**.
