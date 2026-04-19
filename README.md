# 🎵 Web Harmonium

> A beautiful, free, open-source Indian harmonium — playable in any browser. No downloads, no accounts, no plugins.

**[▶ Live Demo →](https://moin-shadab.github.io/web-harmonium/)**

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎹 **Full Keyboard** | 3 octaves of keys, playable by mouse, touch, and computer keyboard |
| ⌨️ **Keyboard Shortcuts** | `A–L` for white keys, `W/E/T/Y/U` for black keys, `Z/X` for octave, `C/V` for transpose |
| 🔊 **Reed Synthesis** | Harmonium-style multi-oscillator synthesis with sawtooth + harmonic layering |
| 🌊 **Reverb** | Built-in convolution reverb with adjustable wet level |
| 🎵 **Raag Scale Highlighting** | Highlights keys for Bilawal, Bhairavi, Yaman, Bhairav, Kafi, Asavari |
| 🎛️ **Timbre Control** | Harmonium / Pure Reed / Flute / Sarangi voices |
| 🎚️ **Extra Reeds** | Adds octave-doubled voice for richer tone |
| 🔁 **Drone** | Continuous Sa drone in any of 12 root notes |
| ⏺️ **Recorder** | Record and play back your performance |
| 🎹 **MIDI Input** | Connect any MIDI keyboard and play (WebMIDI API) |
| 📱 **Touch Support** | Fully playable on phones and tablets |
| 📊 **Live Waveform** | Real-time oscilloscope display |
| 🌙 **Dark Theme** | Beautiful woodgrain-inspired dark instrument aesthetic |
| 🆓 **100% Free** | MIT License, no cost, forever |

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

1. **Fork this repo** (click Fork button top-right)
2. Go to **Settings → Pages**
3. Set Source to **Deploy from branch → main → / (root)**
4. Your harmonium will be live at:
   ```
   https://yourusername.github.io/web-harmonium
   ```

That's it. No build step, no npm, no server needed.

---

## 🎮 How to Play

### Mouse / Touch
Click or tap any key to play it. Hold to sustain.

### Computer Keyboard
```
White keys:  A  S  D  F  G  H  J  K  L  ;  '
             C  D  E  F  G  A  B  C  D  E  F

Black keys:  W  E     T  Y  U     O  P
             C# D#    F# G# A#    C# D#

Z = Octave Down    X = Octave Up
C = Transpose −    V = Transpose +
```

### MIDI Keyboard
Connect any USB MIDI keyboard. The browser will auto-detect it. Press any key.

---

## 🎶 Indian Raag Scales

Select a raag from the dropdown to highlight the correct notes on the keyboard:

| Raag | Swaras | Mood |
|---|---|---|
| Bilawal | Sa Re Ga Ma Pa Dha Ni | Devotional, bright |
| Bhairavi | Sa ra Re ga Ma Pa dha ni | Peaceful, emotional |
| Yaman | Sa Re Ga Ma+ Pa Dha Ni | Romantic, evening |
| Bhairav | Sa ra Ga Ma Pa dha Ni | Serious, morning |
| Kafi | Sa Re ga Ma Pa Dha ni | Folk, light |
| Asavari | Sa Re ga Ma Pa dha ni | Raga of pathos |

---

## 🛠️ Technical Details

- **Pure HTML/CSS/JS** — single file, zero dependencies
- **Web Audio API** — multi-oscillator synthesis, convolution reverb
- **WebMIDI API** — MIDI keyboard input
- **No frameworks** — works in any modern browser
- **< 15KB** — instant load

---

## 📁 File Structure

```
web-harmonium/
└── index.html    ← The entire app
└── README.md     ← This file
```

---

## 📄 License

MIT License — use, modify, and share freely.

---

## ⭐ Support

If you enjoy Web Harmonium, please **star this repo** — it helps others discover it!

---

*Built with ❤️ By Moin Shadab for Indian classical music lovers everywhere.*
