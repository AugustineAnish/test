# 💗 For Nandu — Love Letter Web App

A cinematic, mobile-first love letter web app built with Python (Flask).

## Run locally

```bash
pip install flask
python app.py
# open http://localhost:5000
```

## Deploy FREE in 3 minutes → Render.com

1. Push this folder to a **GitHub repo** (can be private)
2. Go to https://render.com → New → Web Service
3. Connect your GitHub repo
4. Set:
   - **Build command:** `pip install -r requirements.txt`
   - **Start command:** `gunicorn app:app`
   - **Environment:** Python 3
5. Click **Deploy** — you get a public URL like `https://nandu-love.onrender.com`
6. Send her the link 💗

## Alternative: Railway.app

1. Install Railway CLI: `npm install -g @railway/cli`
2. `railway login`
3. `railway init` inside this folder
4. `railway up`
5. Done — Railway gives you a public URL instantly.

## What's inside

- Cinematic starfield background (canvas, 3D parallax)
- Animated beating heart with pulse rings
- Python code block — `love_letter.py` with syntax highlighting
- "Reasons I love you" scroll-reveal cards
- Promise section + day counter
- Easter egg: tap the heart for secret messages
- 100% mobile responsive, works on Android Chrome
