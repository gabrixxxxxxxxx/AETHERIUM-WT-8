# AETHERIUM WT-8

[![WebSynth Live](https://img.shields.io/badge/WebSynth-Live-00f0ff?style=for-the-badge&logo=googlechrome&logoColor=05070a)](https://aetherium-wt-8.pages.dev)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=05070a)](#)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Native%20DSP-b84dff?style=for-the-badge)](#)
[![Polyphony](https://img.shields.io/badge/Polyphony-8%20Voices-ff3b30?style=for-the-badge)](#)
[![FX Rack](https://img.shields.io/badge/FX%20Rack-10%20Units-ffaa00?style=for-the-badge)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-10b981?style=for-the-badge)](#)

**Polyphonic Wavetable Synthesizer** creato da **slitex3K** con l'ausilio di un'Intelligenza Artificiale avanzata. Un sintetizzatore wavetable nativo ad alte prestazioni scritto in puro JavaScript ES6+ e **Web Audio API**, racchiuso in un singolo file `index.html` senza librerie o dipendenze esterne.

> **Prova subito il WebSynth ufficiale:** <https://aetherium-wt-8.pages.dev>

## Caratteristiche Principali

* **Motore Wavetable Polifonico:** Fino a **8 voci** con modalità di voicing **POLY**, **MONO** e **LEGATO** (con controllo *Glide* e *Retrigger*).
* **Oscillatori A & B (64 frame × 1024 campioni):**
  * Wavetable procedurali: *Basic Shapes*, *Digital Growl*, *Acid / PWM*, *FM Harmonics*, *Vocal Formant* e *Metallic Chaos*.
  * Modalità **Warp**: *Off*, *Hard Sync*, *Bend +*, *Bend -*, *PWM Squeeze*, *Asym Fold*, *FM (from Osc B)* e *RM (from Osc B)*.
  * Controlli per *WT Pos*, *Warp*, *Unison* (fino a 7 voci), *Detune*, *Oct*, *Semi*, *Pan*, *Level* e routing verso il filtro (`FLT`).
* **Sub & Noise Generator:**
  * **Sub Osc** (*Sine*, *Triangle*, *Square*, *-1 / -2 OCT*, *Level*, routing `FLT`).
  * **Noise** (*White*, *Pink*, *Crackle*, controllo *Color/Cutoff* e *Level*, routing `FLT`).
* **Multimode Filter Engine:** Modalità *Lowpass 12/24dB*, *Highpass 12/24dB*, *Bandpass 12/24dB*, *Notch*, *Resonant Comb* e *Vowel Formant (A-E-I-O-U)* con *Cutoff*, *Resonance*, *Pre Drive*, *Fat Boost*, *Keytrack* e *Dry/Wet*.
* **Modulazione Avanzata:**
  * **3 Inviluppi (ENV 1–3)** con visualizzazione interattiva e controlli *Attack*, *Decay*, *Sustain*, *Release*.
  * **2 LFO (LFO 1–2)** con forme *Sine*, *Triangle*, *Saw*, *Square*, *S&H*, sincronizzazione *HZ* o *SYNC* (BPM) e *Phase*.
  * **Modulation Matrix a 8 slot** con sorgenti (*Env 1–3*, *LFO 1–2*, *Velocity*) e destinazioni bipolari su oscillatori, filtro ed effetti.
* **Polyphonic Arpeggiator & Chord Memory:**
  * Arpeggiatore con modalità *Up*, *Down*, *Up / Down*, *Poly Chord Pulse* e *Random Poly*, rate ritmiche (*1/4* fino a *1/32*), *Octaves*, *Gate Len*, *Swing*, *Accent* e *Hold / Latch*.
  * *Chord Memory* con preset (*Minor 7th*, *Major 9th*, *Dark Trap 5th+Oct*, *Ethereal Sus2/9*, *Diminished Tension*, *Octave Power*), funzione **Learn Chord**, *Strum Delay* e *Vel Humanize*.
* **Master FX Rack (10 Moduli Seriali):**
  1. *Hyper / Dim*
  2. *Phaser*
  3. *Tape Flanger*
  4. *Bitcrusher* (con *Bits*, *SR* e *Jitter*)
  5. *Distortion* (*Tube Warm*, *Hard Clip*, *Diode Fuzz*, *Wavefold*)
  6. *3-Band EQ* (*Low*, *Mid*, *Air*)
  7. *Widener* (*Width*, *Haas*)
  8. *Oct Shimmer*
  9. *PP Delay*
  10. *Reverb*
* **Preset & Patch JSON:** **14 preset di fabbrica** integrati, funzione **INIT** e **Export / Import (`EXP` / `IMP`)** in formato `.json`.
* **Prestazioni, Sicurezza e Personalizzazione:**
  * **Oversampling (`1x` / `2x` / `4x`)** e modalità **ECO** per ottimizzare la CPU.
  * **Master Safety Limiter** con indicatore di *Gain Reduction* in tempo reale e tasto **PANIC**.
  * **8 Temi Visivi** (*Cyber Cyan*, *Crimson Static*, *Acid Volt*, *Solar Amber*, *Ultraviolet*, *Arctic Ice*, *Toxic Mint*, *Gold Luxe*) e visualizzatore *Scope / FFT* reattivo.

## Controlli & Suonabilità

* **Web MIDI:** Collegamento automatico ai dispositivi MIDI disponibili nel browser.
* **Tastiera QWERTY:**
  * Note: `[A W S E D F T G Y H U J K O L P]`
  * Cambio ottava: `[Z]` (giù) / `[X]` (su)
* **Mouse / Touch:** Tastiera a 3 ottave su schermo, scrubbing diretto sulle forme d'onda dei wavetable e controllo manopole (trascinamento verticale, `Shift` per regolazione fine, doppio clic per il valore di default).

## Avvio Locale

Non è richiesto alcun processo di build o installazione di pacchetti:

1. Clona o scarica la repository.
2. Apri `index.html` in un browser moderno compatibile con la **Web Audio API** (oppure visita direttamente la versione live su <https://aetherium-wt-8.pages.dev>).

## Crediti

* **Autore:** `slitex3K` (sviluppato con l'ausilio di un'Intelligenza Artificiale avanzata).
