# 💬 AI-Powered Funding Recommendation Chatbot

This project is an intelligent chatbot system that helps innovators, students, and startups in India find relevant **funding institutions** based on their project ideas. Using **Natural Language Processing (NLP)**, the chatbot analyzes a user's input and suggests government, CSR, and private funding organizations across domains like technology, healthcare, environment, education, and agriculture.

---

## 🚀 Features

- 🔍 Understands natural language project descriptions
- 📚 Matches your project to relevant funding sectors
- 🏛️ Recommends funding bodies with additional info
- 📄 Displays application steps for selected institutions
- 🧠 Uses tokenization, stopword filtering, and fuzzy matching
- 💡 Runs easily on Google Colab or local Python environment

---

## 📌 Technologies Used

- **Python 3**
- **NLTK** – for text preprocessing
- **FuzzyWuzzy** – for fuzzy keyword matching
- **Text Files** – for funding info and application steps

---

## 🛠️ How It Works

1. User describes their project idea (e.g., "AI app for rural farmers").
2. Input is tokenized and cleaned using NLTK.
3. Tokens are matched to a keyword-category mapping.
4. Matching funders are shown.
5. Optional: View more information and application steps.

---

```bash
pip install nltk
pip install fuzzywuzzy[speedup]
Also download NLTK resources:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('stopwords')
▶️ Run the Chatbot
Run in any Python environment (e.g., Google Colab):

python
Copy
Edit
from chatbot import funding_chatbot_nltk
funding_chatbot_nltk()
