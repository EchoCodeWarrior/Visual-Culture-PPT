# 🎨 AI and the Transformation of Visual Culture

> A cinematic, interactive web presentation exploring how Artificial Intelligence is reshaping visual culture — built with a creative editing console aesthetic.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## ✨ Features

- **Cinematic Slide Transitions** — Smooth fade + slide + scale + 3D rotateY + blur effects with Apple-level cubic-bezier curves
- **Editing Console UI** — Cards feature glassmorphism panels, window dots, LIVE/READY/DRAFT status indicators, mini control buttons, and timeline progress bars
- **DAW/Video Editor Background** — Realistic studio interface with menu bar, toolbar, transport controls, live timecode, 8 named tracks with colored clips and SVG waveforms, animated playhead, and time ruler
- **Render Button Simulation** — Click "Render Final Output" to watch a phased progress animation (pipeline init → video processing → color grading → audio encoding → compositing → finalize), then the video preview fades in
- **25 Slides** covering Introduction, Visual Culture Theory, Semiotics, Historical Evolution, Generative AI, Authorship, Bias, Deepfakes, Economic Impact, Case Study, and more
- **Fully Responsive** — Works on desktop, tablet, and mobile
- **Keyboard & Touch Navigation** — Arrow keys, swipe gestures, dot indicators

## 🖥️ Preview

The presentation features a dark, futuristic creative studio interface:

- 🎬 **Top menu bar** with "AI Studio Pro" branding
- 🎛️ **Toolbar** with select/razor/hand tools, play/skip transport controls, timecode display
- 🎵 **8 Timeline tracks** (V1–V4 video, A1–A4 audio) with named clips and waveforms
- 📊 **Animated playhead** and time ruler

## 🚀 Getting Started

### Run Locally

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/ai-visual-culture-presentation.git
cd ai-visual-culture-presentation

# Serve with any static server
npx http-server . -p 8765 --cors

# Open in browser
# http://127.0.0.1:8765/index.html
```

### Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repository
4. Click **Deploy** — done!

Or via CLI:
```bash
npx vercel --prod
```

## 📁 Project Structure

```
├── index.html          # Self-contained presentation (HTML + CSS + JS inline)
├── vercel.json         # Vercel deployment config
├── presentation.html   # HTML structure (modular version)
├── styles.css          # Stylesheet (modular version)
├── script.js           # JavaScript logic (modular version)
└── README.md           # This file
```

## 🎮 Navigation

| Action | Control |
|---|---|
| Next slide | `→` `↓` `PageDown` or click `>` arrow |
| Previous slide | `←` `↑` `PageUp` or click `<` arrow |
| First slide | `Home` |
| Last slide | `End` |
| Jump to slide | Click any dot indicator |
| Mobile | Swipe left/right |

## 📖 Slide Topics

1. **Title** — AI and the Transformation of Visual Culture
2. **Introduction** to Visual Culture
3. **What is Visual Culture?**
4. **Representation Theory**
5. **Semiotics & Meaning-Making**
6. **Historical Evolution** of Visual Culture (Timeline)
7. **Rise of Digital Media**
8. **Emergence of Generative AI**
9. **What is Generative AI?**
10. **AI as Cultural Producer**
11. **Transformation of Creativity**
12. **Shift in Authorship**
13. **Democratization** of Cultural Production
14. **Algorithmic Bias & Representation**
15. **Power, Platforms & Control**
16. **Authenticity & Deepfakes**
17. **Economic Impact & Job Displacement**
18. **Case Study:** AI Music Video Project
19. **Creative Roles & Collaboration** (Team Cards)
20. **Human-AI Hybrid Production Model** (Flow Diagram)
21. **Sociological Analysis** of the Project
22. **Project Video** (with Render simulation)
23. **Advantages** of AI in Visual Culture
24. **Challenges & Ethical Concerns**
25. **The Future of Visual Culture** (Conclusion)

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, glassmorphism, keyframe animations, responsive grid
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — Inter + JetBrains Mono
- **SVG Icons** — Inline, no icon library needed

## 📄 License

This project is for educational purposes as part of an undergraduate Sociology of Visual Culture course.

---

<p align="center">Built with ❤️ and AI</p>
