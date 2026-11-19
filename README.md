# AETHERIUM WT-8

[![WebSynth Live](https://img.shields.io/badge/WebSynth-Live-00f0ff?style=for-the-badge&logo=googlechrome&logoColor=05070a)](https://aetherium-wt-8.pages.dev)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=05070a)](#)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Native%20DSP-b84dff?style=for-the-badge)](#)
[![Polyphony](https://img.shields.io/badge/Polyphony-8%20Voices-ff3b30?style=for-the-badge)](#)
[![FX Rack](https://img.shields.io/badge/FX%20Rack-10%20Units-ffaa00?style=for-the-badge)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-10b981?style=for-the-badge)](#)

**Polyphonic Wavetable Synthesizer** created by **slitex3K** with the assistance of an advanced Artificial Intelligence. A high-performance native wavetable synthesizer written in pure ES6+ JavaScript and **Web Audio API**, contained within a single `index.html` file with no external libraries or dependencies.

> **Try the official WebSynth right now:** <https://aetherium-wt-8.pages.dev>

## Key Features

- **Polyphonic Wavetable Engine:** Up to **8 voices** with **POLY**, **MONO**, and **LEGATO** voicing modes (including *Glide* and *Retrigger* controls).
- **Oscillators A & B (64 frames × 1024 samples):**
  - Procedural wavetables: *Basic Shapes*, *Digital Growl*, *Acid / PWM*, *FM Harmonics*, *Vocal Formant*, and *Metallic Chaos*.
  - **Warp** modes: *Off*, *Hard Sync*, *Bend +*, *Bend -*, *PWM Squeeze*, *Asym Fold*, *FM (from Osc B)*, and *RM (from Osc B)*.
  - Controls for *WT Pos*, *Warp*, *Unison* (up to 7 voices), *Detune*, *Oct*, *Semi*, *Pan*, *Level*, and routing to the filter (`FLT`).
- **Sub & Noise Generator:**
  - **Sub Osc** (*Sine*, *Triangle*, *Square*, *-1 / -2 OCT*, *Level*, `FLT` routing).
  - **Noise** (*White*, *Pink*, *Crackle*, *Color/Cutoff* and *Level* controls, `FLT` routing).
- **Multimode Filter Engine:** *Lowpass 12/24dB*, *Highpass 12/24dB*, *Bandpass 12/24dB*, *Notch*, *Resonant Comb*, and *Vowel Formant (A-E-I-O-U)* modes with *Cutoff*, *Resonance*, *Pre Drive*, *Fat Boost*, *Keytrack*, and *Dry/Wet*.
- **Advanced Modulation:**
  - **3 Envelopes (ENV 1–3)** with interactive visualization and *Attack*, *Decay*, *Sustain*, and *Release* controls.
  - **2 LFOs (LFO 1–2)** with *Sine*, *Triangle*, *Saw*, *Square*, and *S&H* waveforms, *HZ* or *SYNC* (BPM) synchronization, and *Phase*.
  - **8-slot Modulation Matrix** with sources (*Env 1–3*, *LFO 1–2*, *Velocity*) and bipolar destinations across oscillators, filter, and effects.
- **Polyphonic Arpeggiator & Chord Memory:**
  - Arpeggiator with *Up*, *Down*, *Up / Down*, *Poly Chord Pulse*, and *Random Poly* modes, rhythmic rates (*1/4* up to *1/32*), *Octaves*, *Gate Len*, *Swing*, *Accent*, and *Hold / Latch*.
  - *Chord Memory* with presets (*Minor 7th*, *Major 9th*, *Dark Trap 5th+Oct*, *Ethereal Sus2/9*, *Diminished Tension*, *Octave Power*), **Learn Chord** function, *Strum Delay*, and *Vel Humanize*.
- **Master FX Rack (10 Serial Modules):**
  1. *Hyper / Dim*
  2. *Phaser*
  3. *Tape Flanger*
  4. *Bitcrusher* (with *Bits*, *SR*, and *Jitter*)
  5. *Distortion* (*Tube Warm*, *Hard Clip*, *Diode Fuzz*, *Wavefold*)
  6. *3-Band EQ* (*Low*, *Mid*, *Air*)
  7. *Widener* (*Width*, *Haas*)
  8. *Oct Shimmer*
  9. *PP Delay*
  10. *Reverb*
- **Presets & JSON Patches:** **14 built-in factory presets**, **INIT** function, and **Export / Import (`EXP` / `IMP`)** in `.json` format.
- **Performance, Safety & Customization:**
  - **Oversampling (`1x` / `2x` / `4x`)** and **ECO** mode to optimize CPU usage.
  - **Master Safety Limiter** with real-time *Gain Reduction* meter and **PANIC** button.
  - **8 Visual Themes** (*Cyber Cyan*, *Crimson Static*, *Acid Volt*, *Solar Amber*, *Ultraviolet*, *Arctic Ice*, *Toxic Mint*, *Gold Luxe*) and reactive *Scope / FFT* visualizer.

## Controls & Playability

- **Web MIDI:** Automatic connection to MIDI devices available in the browser.
- **QWERTY Keyboard:**
  - Notes: `[A W S E D F T G Y H U J K O L P]`
  - Octave shift: `[Z]` (down) / `[X]` (up)
- **Mouse / Touch:** On-screen 3-octave keyboard, direct scrubbing on wavetable waveforms, and knob control (vertical drag, `Shift` for fine adjustment, double-click to reset to default value).

## Local Startup

No build process or package installation is required:

1. Clone or download the repository.
2. Open `index.html` in a modern browser that supports the **Web Audio API** (or visit the live version directly at <https://aetherium-wt-8.pages.dev>).

## Credits

- **Author:** `slitex3K` (developed with the assistance of an advanced Artificial Intelligence).
