# Resume-skill-extractor-NLP
🧠 Resume Skill Extractor using NLTK & spaCy


📌 Project Overview

This project is a Python-based Resume Skill Extractor built using NLTK and spaCy.
It processes resume text and automatically extracts:

Candidate Name

Location

Organization

Technical Skills

The project demonstrates the use of Natural Language Processing (NLP) techniques such as tokenization, Named Entity Recognition (NER), and keyword matching.

---

🛠️ Technologies Used

Python

spaCy (Named Entity Recognition)

NLTK (Tokenization)

Regular Expressions (Regex)

---

📂 Input

Resume text provided as a string inside the Python code
(can be extended to .txt file input)

---


📤 Output

The extracted information is displayed in the terminal or notebook output:

Name: Akash Kumar
Location: Bangalore
Organization: Google
Detected Skills: ['Python', 'TensorFlow', 'AWS', 'Docker']

---
⚙️ How It Works

Loads the spaCy English language model

Applies Named Entity Recognition (NER) to extract:

PERSON → Name

GPE → Location

ORG → Organization

Tokenizes resume text using NLTK

Matches tokens with a predefined technical skills list

Displays extracted entities and skills

---

▶️ How to Run

Install dependencies:

pip install spacy nltk
python -m spacy download en_core_web_sm





---
🎯 Learning Outcomes

Practical use of spaCy for entity extraction

Resume parsing using NLP

Keyword-based skill extraction

Real-world text processing

---
👨‍💻 Author

SYEDA ALIA SAMIA
