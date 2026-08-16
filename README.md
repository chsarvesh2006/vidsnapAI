# VidSnapAI 🎬

VidSnapAI is a Flask-based web app for creating AI-powered Instagram-style reels. Upload your media, add a text prompt for narration, and combine everything into a short, shareable video.

Built as part of the CodeWithHarry Python course, then extended as a personal project.

## Features

- **Home page** — Landing page introducing the AI Reel Generator
- **Create Reel** — Upload multiple media files and enter text to be converted into voice narration for your reel
- **Gallery** — Browse previously created reels
- Clean, Instagram-inspired UI (custom CSS, no framework bloat)

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, Jinja2 templates
- **Media:** Static assets (images, audio) bundled for reel creation

## Project Structure

```
template/
├── main.py                # Flask app & routes
├── static/
│   ├── css/                # Stylesheets for each page
│   ├── songs/               # Sample background tracks
│   └── reels/                # Generated reels output
└── templates/
    ├── base.html            # Shared layout
    ├── index.html            # Landing page
    ├── create.html            # Reel creation form
    └── gallery.html            # Reel gallery
```

## Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/<your-username>/vidsnapAI.git
   cd vidsnapAI/template
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app
   ```bash
   python main.py
   ```

4. Open `http://127.0.0.1:5000` in your browser

## Roadmap

- [ ] Hook up backend video/audio processing for the Create Reel flow (e.g. via `moviepy`)
- [ ] Add text-to-speech generation for the narration input
- [ ] Persist and display generated reels in the Gallery
- [ ] Add user authentication

## Author

Sarvesh — B.Tech CSE (AIML), UCEK, JNTUK
