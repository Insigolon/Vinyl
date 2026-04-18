# 💿 Vinyl Library

A beautiful vinyl music player — no server needed, just open in your browser.

## Setup

1. Drop your audio files into the `songs/` folder
2. Open `index.html` in a text editor
3. Find the `PLAYLIST` array near the top of the `<script>` tag
4. Add your songs like this:

```js
const PLAYLIST = [
  { title: "Song Name",      artist: "Artist Name",   file: "songs/song.mp3"   },
  { title: "Another Track",  artist: "Another Artist", file: "songs/track2.mp3" },
  { title: "Third Song",     artist: "Band Name",      file: "songs/third.mp3"  },
];
```

5. Open `index.html` in your browser (double-click it) — done!

## Supported Formats
MP3, WAV, FLAC, OGG, AAC, M4A — anything your browser can play.

## File Structure
```
vinyl-library/
├── index.html      ← the player
├── README.md       ← this file
└── songs/
    ├── song1.mp3
    ├── song2.mp3
    └── ...
```

> **Note:** If you open the HTML file directly from your desktop (file://), 
> some browsers block local audio for security reasons. 
> If that happens, use VS Code's Live Server or Python's simple server:
> `python3 -m http.server` then visit `http://localhost:8000`
"# Vinyl" 
