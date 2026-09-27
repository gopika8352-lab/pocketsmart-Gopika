# PocketSmart AI – Complete Source Code

This folder is the complete runnable application source.

## Setup

```powershell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

Create `.env` from `.env.example` and add your own Gemini API key. Do not commit `.env`.

## Run

```powershell
python app.py
```

Then open:

`http://127.0.0.1:5000`

## Main Source Files

- `app.py` – Flask routes, authentication, planner processing and history.
- `gemini_utils.py` – Gemini integration and safe fallback handling.
- `templates/` – all HTML/Jinja pages.
- `static/style.css` – complete UI styling.
- `requirements.txt` – dependencies.
- `.env.example` – environment configuration template.
