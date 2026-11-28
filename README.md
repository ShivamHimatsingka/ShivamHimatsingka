<h1 align="center">Hi, I'm Shivam 👋</h1>

<p align="center">
  <b>Systems &amp; native app builder from India.</b><br />
  I write lightweight, zero-dependency software that gets close to the hardware.
</p>

<p align="center">
  <a href="https://shivamhimatsingka.github.io/"><img alt="Website" src="https://img.shields.io/badge/website-shivamhimatsingka.github.io-0969da?style=flat-square" /></a>
  <img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" />
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

---

## 🚀 Featured Projects

| Project | What it does | Under the hood |
| :--- | :--- | :--- |
| **[SwiftDrop](https://github.com/ShivamHimatsingka/SwiftDrop)** | AirDrop-style file sharing across **Mac, iPhone, Android & Windows** (LocalSend v2 compatible). | Apple peer-to-peer Wi-Fi (**AWDL**, ~40 MB/s), **BLE wake-up** for locked iPhones, TLS-encrypted disk streaming. |
| **[Conduit](https://github.com/ShivamHimatsingka/conduit)** | Free, open-source virtual audio router and mixer for macOS: a 16-channel virtual device plus a menu-bar mixer. | Custom Core Audio driver, per-app capture via **Core Audio Process Taps**, routing matrix, 60 fps meters with FFT spectrum at ~0.2% of one core, real-time-safe audio path. |
| **[Chromesthesia](https://github.com/ShivamHimatsingka/Chromesthesia)** | Real-time synesthetic visuals for music production: audio in, GPU fluid and HDR light out. | Chord, key, tempo and mood analysis from FFTs, a WebGL2 fluid sim with ~1M particles, and a native Swift audio sender at ~3.5% of one core. |
| **Overdub Studio** | A free digital audio workstation for macOS: records and edits audio and MIDI, hosts AU and VST3 plug-ins, and opens sessions from other DAWs. *(private repo)* | C++20 + **JUCE**, multi-core real-time audio engine, piano roll, mixer with 11 built-in effects, automation, Reaper and DAWproject importers, plug-in scanning in isolated helper processes. |
| **[Plugin Lens](https://github.com/ShivamHimatsingka/PluginLens)** | Native macOS app that lists every plugin a DAW project uses, with the version it was saved with vs. what's installed. Works with **Logic Pro, MainStage, Ableton Live, REAPER, FL Studio, Pro Tools, Cubase, Nuendo, Bitwig, Studio One** and more. | Swift + SwiftUI, no dependencies. Reverse-engineered a dozen undocumented project formats, matches plugins by Audio Unit codes, read-only and offline. |
| **Resonance** | Native macOS room-acoustics tool that needs **no calibrated mic**: measures your room with the built-in mic, finds bass problems, and generates a cut-only EQ it then proves by re-measuring. *(private repo)* | Swift, SwiftUI, **Metal** and Accelerate. Farina sweep deconvolution, rolling-median mode detection, Lundeby RT60, a GPU wave sandbox, ~3 MB and fully offline. |
| **AccessMac** | Native macOS alternative to Microsoft Access that works directly on `.accdb` / `.mdb` files, offline. *(private repo)* | Swift, SwiftUI/AppKit, SQLite. Table, query, form, report and macro designers, relationships with real foreign keys, Access files read and written through Jackcess. |
| **[Meterbar](https://github.com/ShivamHimatsingka/Meterbar)** | macOS menu bar system monitor: CPU, GPU, RAM, SMC temps, disk, network, battery. | **~12 MB RAM**, **0.3% CPU**, a 0.4 MB single-file Swift/AppKit binary. |
| **[FiveK](https://github.com/ShivamHimatsingka/FiveK)** | Turns a 27" 5K iMac into a wireless extended display at its **maximum 5K resolution** (5120×2880). No third-party streaming apps. | Hardware HEVC (`ScreenCaptureKit` + `VideoToolbox`), **zero idle overhead** via `launchd` socket activation, 120 Hz cursor, selectable resolution and optional 4:4:4 colour. |
| **[MIDI Footcontroller](https://github.com/ShivamHimatsingka/MIDI_Footcontroller_Arduino_ProMicro)** | Driver-free 8-button USB MIDI foot controller for guitar rigs and DAWs. | Class-compliant USB MIDI on **ATmega32U4** with hardware debounce and configurable PC/CC messages. |
| **[Graphical Calculator](https://github.com/ShivamHimatsingka/Graphical-Calculator)** ([live](https://shivamhimatsingka.github.io/Graphical-Calculator/)) | Desmos-style graphing calculator with an **offline AI**: ask a question or word problem and get an editable graph, with no internet or API key. Runs in the browser and as a native Mac app. | 2D and 3D graphing, complex domain colouring, geometry and matrix modes, regression. The Mac app bundles **llama.cpp** and a built-in model manager; every result is checked by the calculator's own engine. Swift/SwiftUI + plain HTML/CSS/JS. |

---

## 🛠 What I Build With

- **Apple / Systems:** Swift, AppKit, SwiftUI, ScreenCaptureKit, VideoToolbox, Core Audio (HAL drivers, Process Taps), Accelerate, CoreGraphics, IOKit / SMC, launchd
- **Cross-platform & networking:** Kotlin (Jetpack Compose), .NET 8 / C#, Bluetooth LE, AWDL / Wi-Fi Direct, TLS
- **Graphics & audio:** WebGL2, GLSL, Metal, JUCE (C++20), FFT-based audio analysis, room acoustics DSP, MIDI
- **Embedded & scientific:** C++ (Arduino / ATmega32U4), SQLite, Python (NumPy, SymPy, PySide6), plain HTML/CSS/JS

---

## 📫 Connect

- 🌐 Website: [shivamhimatsingka.github.io](https://shivamhimatsingka.github.io/)
- 💻 GitHub: [@ShivamHimatsingka](https://github.com/ShivamHimatsingka)
