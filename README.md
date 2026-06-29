# Fifine K688 Companion App

A sleek, professional, and lightweight open-source companion application designed specifically for the **Fifine K688** USB Microphone. It leverages the raw DSP power of **Equalizer APO** to bring studio-quality processing directly to your desktop, with an intuitive, modern interface.

## 🌟 Features

- **True Hardware Integration:** Automatically detects the Fifine K688 and writes DSP parameters directly to the Equalizer APO configuration file (`config.txt`) in real-time with zero latency.
- **Smart Noise Gate:** Includes a highly requested **Auto-Calibrate** feature. It listens to your room for 5 seconds and perfectly sets your noise floor threshold.
- **10-Band Graphic & Parametric EQ:** A gorgeous HTML5 canvas-based Equalizer. Click and drag nodes to sculpt your frequency response. Choose between precise Parametric or broad Graphic modes.
- **Live Soundwave Visualizer:** Watch your voice in real-time with a smooth, 60fps glowing waveform visualization that reacts dynamically to your speech.
- **Complete Channel Strip:**
  - Gain Stage (Input & Output trim)
  - Noise Gate (Attack, Release, Threshold)
  - Compressor (Ratio, Threshold, Makeup Gain)
  - De-Esser (Frequency target, Threshold)
  - Limiter (Ceiling)
- **Built-in Audio Monitor:** Hear the effects of your EQ, Compression, and Gate applied instantly to your voice in a Javascript-based internal Web Audio API replica, without needing a DAW or OBS open to test your mic.
- **Preset Management:**
  - Comes with 7 hardware-tailored Factory Presets (Podcast Warm, ASMR, Loud Gamer, etc.)
  - Save and delete unlimited custom User Presets directly from the sidebar.
  - Import and Export presets as `.json` files to share with the community!
- **Dark & Light Mode:** Toggle between an immersive dark studio theme and a crisp light mode.
- **Audio Diagnostics:** Protects your audio quality by warning you if your Windows Sound Control Panel isn't matching the optimal 48000Hz / 24-bit studio format.

## 🚀 Installation

1. **Install Equalizer APO** (Required)
   - Download [Equalizer APO](https://sourceforge.net/projects/equalizerapo/).
   - In the Configurator, check the box next to your `Fifine K688` microphone.
   - Restart your computer.
2. **Install the Companion App**
   - Download the latest `.exe` from the Releases page.
   - Run the installer.
3. **Plug and Play!**
   - The app will automatically detect your microphone. Tweak the knobs and enjoy!

## 🛠️ Built With

- **Electron** (Cross-platform desktop framework)
- **React 18** (UI rendering)
- **Vite** (Next-generation frontend tooling)
- **Vanilla CSS** (No heavy UI frameworks—just pure, blazing fast CSS variables and glassmorphism)
- **Equalizer APO** (The core audio engine)

---
*Note: This is an unofficial community project and is not affiliated with Fifine.*
