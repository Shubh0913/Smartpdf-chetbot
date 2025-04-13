
# SmartPDF ChatBot

### Built by [shubh soni] | 2025

Ek simple lekin powerful chatbot jo PDF files se sawalon ke jawab de sakta hai. Isme maine **LangChain**, **FAISS**, **OpenAI**, aur **Streamlit** ka use kiya hai. Iska main idea ye tha ki agar koi apna resume, notes, ya koi document upload kare, to wo usi file se related sawal poochh sake — bina pura document padhe.

---

## Features:
- Upload any PDF
- Chat with your PDF (in natural language)
- Fast & accurate response using LLM
- User-friendly UI with Streamlit

---

## Tools & Tech Used:
- Python
- LangChain
- OpenAI API
- FAISS Vector Store
- Streamlit
- PyPDF2

---

## How It Works (Short Summary):

1. PDF ko text mein convert karta hai
2. Text ko chhoti-chhoti chunks mein todta hai
3. Har chunk ka embedding generate hota hai (using OpenAI)
4. FAISS mein store karke fast search hoti hai
5. Jab user sawal poochta hai, uska relevant context nikal ke LLM se answer liya jata hai

---

## Run Locally:

```bash
git clone https://github.com/username/smartpdf-chatbot.git
cd smartpdf-chatbot
pip install -r requirements.txt
streamlit run app.py
