# 📻 HEX RADIO

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://hexsleuth.github.io/HEX-RADIO/)
[![No Tracking](https://img.shields.io/badge/Privacy-No_Cookies-blue.svg)](#)
[![100% Client-Side](https://img.shields.io/badge/Architecture-Client--Side-orange.svg)](#)

**HEX RADIO** is a lightweight, purely client-side web radio player designed to discover, stream, and explore live chart, AM, and FM radio stations from across the globe. Built to run entirely inside any modern web browser without requiring accounts, software downloads, or external plugins, it delivers a seamless, ad-free listening experience.

---

## ✨ Features

* **Live Worldwide Streaming:** Access thousands of internet radio, AM, and FM feeds globally.
* **Top Charts Integration:** View live worldwide music charts. Tap any chart entry to instantly find stations currently playing that song or artist.
* **Privacy First (Zero Cookies):** HEX RADIO hosts no audio, tracks no user data, and stores no cookies. Everything runs locally in your browser.
* **Robust CORS Relay Pool:** Ships with an unlimited pool of 35+ public CORS relays. Direct directory requests are attempted first, automatically falling back through relays if blocked by browser policies to ensure uninterrupted access.
* **HEX Sleuth FM:** A built-in virtual tuner experience providing quick access to featured frequencies and stations.
* **Deep Customization:** Tailor your interface with **34 curated palettes**, custom color pickers, and a permanently enforced, highly readable dark mode.
* **Mobile Ready:** Fully responsive layout optimized for mobile screens with touch-friendly controls.

---

## 🛠️ Architecture & Data Sources

HEX RADIO operates completely in the browser. There is no backend server tracking your listening habits or processing audio. 

* **Station Index:** Powered by the open [Radio-Browser API](https://www.radio-browser.info/).
* **Chart Data:** Live worldwide music charts sourced via reliable relays and top-charts metrics.
* **Audio Playback:** Streams connect directly from the original broadcasters to your browser's native `<audio>` element.

---

## 🚀 Usage

No installation, no npm scripts, and no dependencies required.

1. Open the web app at [**hexsleuth.github.io/HEX-RADIO**](https://hexsleuth.github.io/HEX-RADIO/).
2. Browse through global stations, explore the top charts, or search for your favorite genres.
3. Tap any station to start live streaming instantly.
4. Open the **Settings** menu to customize your theme or manage your active CORS relays.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](../../issues) if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Streams are provided by the broadcasters themselves. HEX RADIO hosts no audio content.*
