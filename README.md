# 🍶 Soju's K-Drama Match

Tell Soju something you loved :a show, film, anime, or game -> and it finds you the K-drama with the same emotional DNA.

---

## What it does

You type something like *"I loved Breaking Bad"* or *"I just finished Attack on Titan"* and Soju:
1. Tells you what it understood about why you loved it
2. Recommends 3 real K-dramas that deliver the same feeling

---

## Files

| File | What it is |
|---|---|
| `kdrama_app.py` | The Streamlit chat app |
| `kdrama_GPT_API.ipynb` | Notebook with code walkthrough and experiments |
| `.env` | Your API key (not shared) |

---

## How to run it

**1. Add your API key**
Rename `.env.example` to `.env` and paste your OpenAI key:
```
OPENAI_API_KEY=your-key-here
```

**2. Install dependencies**
```bash
pip install openai streamlit python-dotenv
```

**3. Launch the app**
```bash
streamlit run kdrama_recommender_app.py
```

---

## Built with

- [OpenAI GPT-3.5 Turbo](https://platform.openai.com/docs) — Chat Completions API
- [Streamlit](https://streamlit.io) — chat interface
- Python · python-dotenv

---
