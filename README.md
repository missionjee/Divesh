# Divesh Kumar — Personal Website & Portfolio

Modern, high-performance personal portfolio and projects directory for **Divesh Kumar** ([@missionjee](https://github.com/missionjee)), Class 11th student developer and IIT-JEE aspirant.

## 🚀 Highlights & Features
- **Modern Clean Theme & Design**: Deep obsidian aesthetics, subtle cyber radial glow, glassmorphism, responsive mobile-first typography, and light/dark mode switch.
- **Dynamic Projects Directory**: Projects are dynamically rendered from `projects.json` without hardcoding project data in HTML.
- **Zero-Code Dynamic Categories**: Categories are automatically extracted and generated from project metadata — adding new categories never requires code changes.
- **Project Cards**: Includes thumbnails, category badges, summaries, technology chips, direct links, and deep-dive modals.
- **Journey & Academics**: Focus on Class 11th PCM preparation alongside software engineering utilities.
- **Clean Separation**: Built with pure vanilla JavaScript, modern Tailwind CSS, and Lucide Icons.

## 📂 Architecture
```text
Divesh/
├── index.html        # Main personal website & dynamic rendering engine
├── projects.json     # Dynamic projects dataset
├── profile.json      # Dynamic profile and bio details
├── assets/           # Profile images and project media
│   └── avatar.png
├── .gitignore        # Keeps local admin and temporary files excluded
└── README.md         # Project documentation
```

## 🛠️ Local Preview
Open `index.html` directly in any modern web browser or serve via any static HTTP server:
```bash
python3 -m http.server 8080
```
Visit `http://localhost:8080` to view the website.
