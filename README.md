# 🌿 Āyurveda Wellness Chatbot

> Discover your Prakriti (mind-body constitution) and receive a fully personalized Ayurvedic wellness plan — diet, lifestyle, herbs, yoga, and more.

[![Deploy to GitHub Pages](https://github.com/YOUR-USERNAME/ayurveda-wellness/actions/workflows/deploy.yml/badge.svg)](https://github.com/YOUR-USERNAME/ayurveda-wellness/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-c4602a?style=flat&logo=github)](https://YOUR-USERNAME.github.io/ayurveda-wellness/)
![No Dependencies](https://img.shields.io/badge/dependencies-zero-2d5a3d)
![Free](https://img.shields.io/badge/cost-free-e8a030)
![License](https://img.shields.io/badge/license-MIT-7a9cbe)

---

## 🌐 Live Demo

**→ [YOUR-USERNAME.github.io/ayurveda-wellness](https://YOUR-USERNAME.github.io/ayurveda-wellness/)**

*(Replace `YOUR-USERNAME` with your actual GitHub username after forking)*

---

## ✨ What It Does

Takes you through an **8-question Prakriti assessment** to determine your dominant Ayurvedic body type (dosha), then delivers a complete personalized wellness report:

| Category | What You Get |
|---|---|
| 🥗 **Diet** | Foods to favour and foods to reduce, specific to your dosha |
| 🌅 **Lifestyle** | Daily routine, exercise type, sleep, and seasonal advice |
| 💡 **Wellness Tips** | 5 practical habits tailored to your constitution |
| 🌿 **Herbs** | 5 Ayurvedic herbs with explanations |
| 🧘 **Yoga** | Poses and pranayama matched to your dosha |
| 🪷 **Q&A** | 4 detailed follow-up questions answered for your type |

---

## 🚀 Instant Setup — 5 Minutes to Live

### Step 1 — Fork this repository

Click the **Fork** button at the top-right of this page.

### Step 2 — Enable GitHub Pages

1. Go to your forked repo → **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. Click **Save**

### Step 3 — Trigger a deployment

Either:
- Push any small change (e.g., edit this README), **or**
- Go to **Actions** → **Deploy to GitHub Pages** → **Run workflow**

### Step 4 — Visit your live URL

```
https://YOUR-USERNAME.github.io/ayurveda-wellness/
```

That's it. Your app is live. ✅

---

## 💻 Run Locally

No build step, no install, no Node.js needed.

```bash
# Clone
git clone https://github.com/YOUR-USERNAME/ayurveda-wellness.git
cd ayurveda-wellness

# Open directly (macOS)
open index.html

# Open directly (Linux)
xdg-open index.html

# Open directly (Windows)
start index.html

# Or serve with Python
python -m http.server 8080
# → http://localhost:8080
```

---

## 📁 Repository Structure

```
ayurveda-wellness/
├── index.html                  ← The entire app (HTML + CSS + JS, self-contained)
├── .github/
│   └── workflows/
│       └── deploy.yml          ← GitHub Actions — auto-deploy on push to main
├── README.md                   ← This file
├── LICENSE                     ← MIT License
└── .gitignore                  ← Standard web gitignore
```

---

## 🔬 How the Scoring Works

```
8 questions × 3 options each
Every option awards 3 points to one dosha (Vata / Pitta / Kapha)
Maximum score per dosha: 24 pts

Result = highest-scoring dosha
Percentage = (dosha score ÷ total) × 100
```

If your second dosha scores ≥ 30%, a secondary dosha note is shown — most people are dual-dosha types.

---

## 🛠 Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Logic | Vanilla JavaScript ES6+ |
| Fonts | Google Fonts (Cormorant Garamond + DM Sans) |
| Backend | **None** |
| Database | **None** |
| Dependencies | **Zero** |
| Build tool | **None** |

---

## 🎨 The Three Doshas

| Dosha | Elements | Qualities | Signs of Imbalance |
|---|---|---|---|
| 🌬 **Vata** | Air + Ether | Creative, quick, changeable | Anxiety, dryness, insomnia |
| 🔥 **Pitta** | Fire + Water | Driven, focused, intelligent | Anger, inflammation, burnout |
| 🌿 **Kapha** | Earth + Water | Calm, stable, nurturing | Lethargy, weight gain, attachment |

---

## ✏️ Customizing

All content lives inside `index.html`. Open it in any text editor.

**Add a question** → find `const QUESTIONS = [` and add a new object  
**Edit recommendations** → find `const DOSHA = {` and edit any `eat`, `avoid`, `lifestyle`, `herbs` arrays  
**Change colors** → edit `:root { }` CSS variables at the top of `<style>`  
**Change fonts** → swap the Google Fonts URL in `<head>` and update `--font-display` / `--font-body`

---

## 📄 License

MIT — free to use, fork, modify, and distribute.

---

## ⚠️ Disclaimer

This app is for educational and wellness purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. For a complete Prakriti assessment, consult a qualified Ayurvedic practitioner (Vaidya).

---

<div align="center">

**☽ ✦ ☾**

*May your path to wellness be guided by wisdom* 🙏

Made with love · Powered by ancient wisdom · Zero dependencies

</div>
