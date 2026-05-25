# 🏋️ AI Gym Coach — Landing Page

Marketing and product landing page for the Realtime Voice & Video AI Gym Coach — an AI-powered fitness trainer that uses computer vision and LLM voice coaching to guide workouts in real time.

## 🔗 Quick Links
* 🌍 **Live Landing Page:** [ai-realtime-gym-trainer.netlify.app](https://ai-realtime-gym-trainer.netlify.app/)
* 🚀 **Live App:** [ai-realtime-gym-trainer.streamlit.app](https://ai-realtime-gym-trainer.streamlit.app/)
* 💻 **Main Project Repo:** [Realtime-Voice-Video-AI-Coach-Mediapipe-Llamaa](https://github.com/AshishShetty1854/Realtime-Voice-Video-AI-Coach-Mediapipe-Llamaa)

## 📄 About This Repo
This repository contains the static landing page for the AI Gym Coach project. It is a pure HTML/CSS site with no frameworks or build tools — just open `index.html` in a browser.

### Sections
* **Hero** — Headline, key metrics (100ms latency, 5+ exercises, 95% form accuracy), and CTA to the live app.
* **Gallery** — Showcase images of the coach in action across different exercises.
* **Demo** — Embedded demo video (`AI_GYM_Trainer_Demo.mp4`).
* **Contact** — Links to LinkedIn, GitHub, and email.

## 🗂️ Structure
```text
Realtime-Voice-Video-AI-Coach-Web/
├── index.html       # Main landing page
├── style.css        # All page styles
├── IMGs/            # Gallery images (Img_1.png … Img_7.png)
├── fonts/           # Local Averta font (woff2)
└── videos/    
    └── AI_GYM_Trainer_Demo.mp4   # Demo video

```
--- 

# 🛠️ Tech Stack

- **HTML5**
- **CSS3** (custom properties, animations, grid layout)
- **Google Fonts** — Ubuntu & Instrument Serif
- **Local Font** — Averta (`.woff2`)

---

# 🚀 Running Locally

No build step needed. Just open the file directly:

```bash
# Option 1 — Open directly
open index.html

# Option 2 — Serve with Python (avoids CORS issues with local video/fonts)
python -m http.server 8080

# Then visit:
http://localhost:8080

```
---

# ☁️ Deploying

This is a static site and can be deployed to any static host.

### GitHub Pages
Enable under:

`Settings → Pages → Deploy from main branch`

### Netlify
Drag and drop the repo folder.

### Vercel
Import the repository and deploy as a static site.

---

# 👤 Author

**Ashish Shetty**

- 🔗 LinkedIn: [Ashish Shetty](http://linkedin.com/in/ashish-shetty-322b29216)
- 🐙 GitHub: [AshishShetty1854](https://github.com/AshishShetty1854)
- 📧 Email: ashishshetty142@gmail.com