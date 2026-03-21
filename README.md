# Level Up — Rhythm Reading Practice

A rhythm reading practice app for music students using the Kodály syllable system.

## How to use
Open `index.html` via a web server (e.g. GitHub Pages). The app requires a server because it loads SVG assets from the `assets/` folder — it will not work by double-clicking the HTML file locally.

## Folder structure
```
rhythm-app/
├── index.html              — main app
├── README.md
└── assets/
    └── svg/
        ├── notes/          — note & rest SVGs (ta, ti-ti, tika-tika, etc.)
        ├── bear/           — bear animation frames (5 states)
        ├── barlines/       — bar line, double bar line, repeat sign
        └── ui/             — drum clef, count-in numbers, toggle icons
```

## Features
- 8 difficulty levels (crotchets through to triplets)
- Time signatures: 2/4, 3/4, 4/4, 5/4
- Configurable bars, tempo, count-in, repeats
- Drum sound, metronome, bar/note highlighting
- Three play modes: Duet, Listen First, Play First
- Animated bear percussionist
