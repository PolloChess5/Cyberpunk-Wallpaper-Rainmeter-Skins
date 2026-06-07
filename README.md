# 🌆 Cyberpunk Rainmeter Suite
A collection of minimal, cyberpunk-styled Rainmeter skins designed for high performance, sleek aesthetics, and quick desktop access. 

![Made with ❤️ by PolloChess5](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square)
![License](https://img.shields.io/github/license/Pollochess5/SpotifyAudioTerminal?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)

---

## 🎧 SpotifyAudioTerminal
A minimal audio player interface with WebNowPlaying integration for controlling music directly from web browsers and local apps.

### ✨ Features
- 🎵 **Web Music Control**: Full support for Spotify and Windows media players.
- 📻 **Live Metadata**: Real-time track information and status display.
- ⏱️ **Visual Feedback**: Dynamic progress bar with accurate time indicators.
- ⏯️ **Media Control**: Clickable play, pause, previous, and next controls.
- 🟣 **Cyberpunk Aesthetic**: Modern layout featuring custom hover effects and transparency.
- 📐 **Compact Layout**: Highly optimized 280x220px footprint.

### ⚙️ Requirements & Compatibility
- 💾 **Rainmeter 4.0+**
- 🌐 **WebNowPlaying Plugin**
- ✅ **Support**: Spotify (web/desktop), Windows built-in media players.
- ⚠️ **Note**: Additional browser players may require the WebNowPlaying browser extension.

---

## 🗓️ Red Cyberpunk Date Timeline
A temporal tracking interface displaying a futuristic, rolling timeline of past, present, and upcoming dates.

### ✨ Features
- 📅 **Dynamic Timeline**: Simultaneously tracks and visualizes the current day, date, month, and year.
- ⏭️ **Temporal Context**: Automatically generates relative indicators for yesterday and tomorrow.
- 🔴 **Neon Styling**: Built using high-contrast red accents, custom bounding boxes, and stylized borders.
- 🌍 **Localization Ready**: Native translation support through internal language variables (Italian default configuration included).

### ⚙️ Requirements
- 💾 **Rainmeter 4.0+**

### 🛠️ Configuration Variables
Modify these values inside the skin's `[Variables]` section to change its appearance:

| Variable | Description |
| :--- | :--- |
| `FontSize` | Adjusts the text scale of the current date indicator. |
| `FontFace` | Swap typography families (Default: `Consolas`). |
| `BGcolor` | Fine-tune the transparency and color depth of the canvas background. |
| `BorderColor` | Changes the color scheme of the surrounding bounding box. |

---

## 🖥️ System Monitor
A compact performance dashboard providing immediate hardware feedback with localized status plots.

### ✨ Features
- 📊 **Real-time Monitoring**: Evaluates RAM footprint, CPU load, and GPU thermal thresholds via real-time line charts.
- 🌡️ **HWiNFO Integration**: Precision hardware query paths pulling directly from the host environment registry.
- 🖱️ **Interactive Refreshes**: Left-clicking any numeric reading instantly hot-reloads the active layout configuration.
- 📐 **Compact Layout**: Tailored 280x90px profile designed to fit minimal desktop spaces.

### ⚙️ Requirements
- 💾 **Rainmeter 4.0+**
- 🌡️ **HWiNFO64** (Must be running for continuous GPU telemetry updates)

### 💻 HWiNFO Configuration Setup
To properly map the GPU temperature sensor data to your dashboard:
1. Open **HWiNFO64**.
2. Navigate to configuration and ensure **Shared Memory Support** is actively checked.
3. Locate your hardware sensor array block and identify the precise index string for your GPU core temperature.
4. Open the skin's `.ini` file and change `GPUTempIndex` to match that specific index.

### 🛠️ Configuration Variables
Modify these parameters in the system monitor `[Variables]` block:

| Variable | Description |
| :--- | :--- |
| `RAMcolor` / `CPUcolor` / `DiskColor` | Tailor individual HEX/RGB lines and color nodes per component category. |
| `GraphWidth` / `GraphHeight` | Scale the performance graph dimensions to alter density. |
| `FontName` | Applies custom font packages across labels and numerical values. |

---

## 🖼️ Media & Gallery

### Desktop Screenshots
![Component Dashboard Screenshot](https://imgur.com/a/ZiSjFvd)

### Desktop Customization Resources
- **Wallpaper Engine Link:** [Osaka Midnight Porsche 911 Live Wallpaper](https://moewalls.com/anime/osaka-midnight-porsche-911-live-wallpaper/)
- **Video Source Link:** [MoeWalls Wallpaper Preview](https://moewalls.com/anime/osaka-midnight-porsche-911-live-wallpaper/)

---
*Designed by PolloChess5 helped by AI*
