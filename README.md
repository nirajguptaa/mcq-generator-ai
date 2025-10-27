# MCQ Generator using LangChain & Ollama

## Project Overview
The **MCQ Generator** is a Python-based tool that automatically generates multiple-choice questions (MCQs) from any input text. It leverages **LangChain** and **Ollama** to create high-quality, topic-specific quizzes with difficulty evaluation and refinement for better learning outcomes.

---

## Features
- Generate MCQs from any text.
- Customize:
  - Number of questions
  - Subject/topic
  - Tone (simple, academic)
- Contextually accurate and unique questions.
- Difficulty evaluation and refinement.
- Export quizzes as a **pandas DataFrame** for easy analysis or export.
- Fully **offline** using local Ollama models.

---

## Tech Stack
- **Python 3.8+**
- **LangChain** – LLM chains and prompt templates
- **Ollama** – Local LLM inference
- **PyPDF2** – Optional, for reading PDFs
- **pandas** – Data manipulation

---

## Installation

### 1. Clone the Repository
```bash
git clone <https://github.com/nirajguptaa/mcq-generator-ai/tree/main>
cd mcqgen

```
---



2. Setup Environment
```bash
conda create -p ./env python=3.8 -y
conda activate ./env

```
3. Install Dependencies
```bash
pip install -r requirements.txt

```
4. Setup Ollama (Mac recommended)
```bash
brew install ollama
ollama pull llama2   # Pull your preferred model
ollama serve         # Start Ollama server
```


---
## 🎯 Usage
- Place your input text in data.txt.
- Run the notebook or script (experiments/mcq.ipynb or src/mcqGenerator/).

---

## Notes
- Ollama must be running (ollama serve) to use the LLM.
-	Fully offline; no OpenAI API required.
-	Works with PDFs if you integrate PyPDF2 (optional).

---
## Author

Niraj Kumar Gupta
