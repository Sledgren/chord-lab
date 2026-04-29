# GlitchRealm Chord Builder

**A free browser-based chord generation and playback tool for producers.**  
Built by [GlitchRealm](https://glitchrealm.com) · No install · No sign up · Works in any browser

---

## What It Is

GlitchRealm Chord Builder is a lightweight but powerful chord tool designed for music producers who need fast, musical chord ideas without leaving their workflow. Drop it in a browser tab, on your website, or embed it directly into a Squarespace page as a code block.

It covers **31,500 chord combinations** across 12 roots, 25 chord types, 7 voicings, and 15 progressions — all playable with your computer keyboard and exportable as named MIDI files.

---

## Features

### Chord Generation
- **12 root notes** — C through B
- **25 chord types** — Major, Minor, Dominant 7, Major 7, Minor 7, Diminished, Augmented, Sus2, Sus4, Add9, 6th, 9th, 11th, 13th, and more
- **7 voicings** — Close, Open, Drop 2, Drop 3, Spread, Quartal, Cluster
- **15 chord progressions** — I–IV–V–I, ii–V–I, I–V–vi–IV, and more classic progressions

### Instruments
8 synthesized instruments, no samples required:
- Grand Piano
- Electric Piano (Rhodes)
- Wurlitzer
- Hammond Organ
- Synth Pad
- Pluck / Harp
- Bell
- Bass

### Keyboard Input
Play chords directly from your computer keyboard — no MIDI controller needed:

| Keys | Function |
|------|----------|
| `A S D F G H J K L` | White keys (C D E F G A B C D) |
| `W E T Y U O P` | Black keys (C# D# F# G# A#...) |
| `Space` | Add current chord to stack |
| `Enter` | Play the full chord stack |
| `Esc` | Stop all playback |

### Chord Stacking
Build progressions on the fly:
- Add chords to a stack one at a time using `Space`
- Play the entire stack back in sequence with `Enter`
- Clear or rearrange the stack at any time

### MIDI Export
- Export any chord or progression as a `.mid` file
- Files are named automatically (e.g. `Cmaj7_Drop2.mid`)
- Compatible with FL Studio, Ableton, Logic, and any DAW that accepts MIDI

---

## How to Use

### In the Browser
1. Open `index.html` in Chrome, Firefox, or Safari
2. Select your root note, chord type, voicing, and instrument
3. Click a chord button or press the corresponding keyboard key to play
4. Stack chords and press `Enter` to hear a progression
5. Click **Export MIDI** to download a `.mid` file

### Embed on Squarespace
1. In the Squarespace editor, add a **Code Block** to your page
2. Paste the contents of `index.html` into the code block
3. Make sure **Display Source Code** is set to **OFF**
4. Save and publish — the tool renders live on your page

### Host on GitHub Pages
1. Create a new public repository (e.g. `chord-lab`)
2. Upload `index.html` — rename it to `index.html` if needed
3. Go to **Settings → Pages**, set source to **main / root**
4. Your tool is live at `https://yourusername.github.io/chord-lab`

---

## File Structure

```
index.html        ← The entire tool, self-contained, zero dependencies
README.md         ← This file
```

Everything runs in a single HTML file. No frameworks, no build steps, no external dependencies. The synthesizer is built using the Web Audio API and runs entirely in the browser.

---

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome / Chromium | ✅ Full support |
| Firefox | ✅ Full support |
| Safari | ✅ Full support |
| Edge | ✅ Full support |
| Mobile Chrome | ✅ Touch supported |
| Mobile Safari | ✅ Touch supported |

---

## Technical Notes

- **No server required** — runs entirely client-side
- **No samples** — all audio synthesis uses the Web Audio API
- **MIDI export** — generates standard Type 0 MIDI files in the browser
- **Embed-safe** — the entire CSS is scoped under `#gr3` so it never conflicts with host page styles
- **Responsive** — adapts to narrow embeds and mobile viewports

---

## About GlitchRealm

GlitchRealm makes free browser-based music production tools for producers.

- 🌐 [glitchrealm.com](https://glitchrealm.com)
- 🎹 [MIDI Visualizer](https://glitchrealm.com/midi-visualizer) — browser MIDI visualization and MP4 export tool
- 🎵 Chord Builder — this tool

---

## License

Free to use for personal and commercial music production.  
Do not redistribute or resell the tool itself as a standalone product.  
© GlitchRealm
