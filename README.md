# 🧠 NLPCommandX

A terminal-based NLP application built using Python and NLPCloud API.  
It uses object-oriented programming to provide smart NLP functionalities like:

- Named Entity Recognition (NER)
- Grammar and Spelling Correction
- Sentiment Analysis
- Headline Generation
- User Registration & Login System

---

## 🚀 Features

- 🔍 **NER**: Detect names, places, organizations, etc.
- ✍️ **Grammar Fix**: Corrects grammar and spelling mistakes.
- 😊 **Sentiment Analysis**: Understands the mood of the text.
- 📰 **Headline Generator**: Creates headlines from any paragraph.
- 🔐 **Login/Register System**: Auth via in-memory database.

---

## 📦 Tech Stack

- **Python 3.x**
- **NLPCloud SDK**
- Language Models:
  - `finetuned-llama-3-70b`
  - `t5-base-en-generate-headline`

---

## 💡 How to Use

```bash
# Step-by-step setup to run the project

git clone https://github.com/your-username/NLPCommandX.git && \
cd NLPCommandX && \
pip install nlpcloud && \
# 👇 Don't forget to update the Python file with your real NLPCloud API key:
# client = nlpcloud.Client("model_name", "your-api-key", gpu=True)
python nlp_app.py


**Sample Flow**


Hi! How would you like to proceed?
1. Register
2. Login
3. Exit

> 2

Enter email: you@example.com
Enter password: ********

Login successful!

Choose your operation:
1. NER
2. Grammar Check
3. Sentiment
4. Headline Generator
5. Logout
```
**Staying curious and getting better with every line of code. 🚀**
