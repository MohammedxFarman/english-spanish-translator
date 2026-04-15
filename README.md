
---

# 🌍 English → Spanish Translator

A simple dataset-based translation app built using Python and Streamlit.

---

## 🚀 Features

- Translates English sentences to Spanish
- Uses dataset (`spa.txt`)
- Cleans input text for better matching
- Simple and fast lookup-based system
- Interactive UI

📄 Code: :contentReference[oaicite:1]{index=1}  

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Regex

---

## 📊 How It Works

- Loads bilingual dataset
- Cleans sentences (lowercase, remove symbols)
- Stores mappings in dictionary
- Performs exact match lookup

---

## 📂 Project Structure
├── app.py (rename app(1).py → app.py)
├── spa.txt
├── README.md


---

## ⚙️ Installation

```bash
git clone https://github.com/MohammedxFarman/english-spanish-translator.git
cd english-spanish-translator
pip install streamlit
streamlit run app.py
