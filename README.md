<div align="center">

# ⚡ cerealkiller57540

**Home Assistant custom cards with a neon / Neo Tokyo soul.**
Sysadmin by day — SCCM, Active Directory, Azure, purple team.

WebGL fluid solver · 3D · live shaders · Web Components · full visual editors, in English and French.

[![Home Assistant][ha-badge]][ha-url]
[![HACS][hacs-badge]][hacs-url]
[![License: MIT][license-badge]][license-url]
[![Home Assistant Core contributor][core-badge]][core-pr]

</div>

---

## 🌃 The neon cards

Ten cards, each in its own repository so HACS can install and update it on its
own. Full gallery, screenshots and one-click install:
**[Home-Assistant-Neon-Cards →](https://github.com/cerealkiller57540/Home-Assistant-Neon-Cards)**

| | Card | |
|:---:|---|---|
| <img src="https://raw.githubusercontent.com/cerealkiller57540/weather-neon-card/main/images/scenes.jpg" alt="Weather Neon Card" width="260"> | [**Weather Neon Card**](https://github.com/cerealkiller57540/weather-neon-card)<br>Weather with a live WebGL sky: rain on the glass, fog, frost, snow, lightning and the real moon phase. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=weather-neon-card&category=plugin) |
| <img src="https://raw.githubusercontent.com/cerealkiller57540/neon-climate-card/main/images/heat.png" alt="Neon Climate Card" width="260"> | [**Neon Climate Card**](https://github.com/cerealkiller57540/neon-climate-card)<br>Climate control with the airflow drawn by a real WebGL fluid solver. Full visual editor. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=neon-climate-card&category=plugin) |
| <img src="https://raw.githubusercontent.com/cerealkiller57540/storey-battery-card/main/images/discharge.png" alt="Storey Battery Card" width="260"> | [**Storey Battery Card**](https://github.com/cerealkiller57540/storey-battery-card)<br>A 3D home battery stack with live electric arcs between the modules. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=storey-battery-card&category=plugin) |
| <img src="https://raw.githubusercontent.com/cerealkiller57540/nixie-clock-card/main/images/main.png" alt="Nixie Clock Card" width="260"> | [**Nixie Clock Card**](https://github.com/cerealkiller57540/nixie-clock-card)<br>Six IN-14 nixie tubes with glowing gas and an acrylic base. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=nixie-clock-card&category=plugin) |
| <img src="https://raw.githubusercontent.com/cerealkiller57540/linux-terminal-card/main/images/main.png" alt="Linux Terminal Card" width="260"> | [**Linux Terminal Card**](https://github.com/cerealkiller57540/linux-terminal-card)<br>A sci-fi CRT terminal showing the health of a Linux PC — CPU, RAM, temperature, battery, network, updates. Real WebGL tube or plain CSS. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=linux-terminal-card&category=plugin) |
| <img src="https://raw.githubusercontent.com/cerealkiller57540/neon-dual-gauge-card/main/images/main.png" alt="Neon Dual Gauge Card" width="260"> | [**Neon Dual Gauge Card**](https://github.com/cerealkiller57540/neon-dual-gauge-card)<br>Two concentric LED gauges with a WebGL plasma core that follows the value. | [![Open in HACS][hacs-btn]](https://my.home-assistant.io/redirect/hacs_repository/?owner=cerealkiller57540&repository=neon-dual-gauge-card&category=plugin) |

### Try one in two minutes

Each card installs from HACS as a custom repository: **HACS → ⋮ → Custom repositories**,
paste the card's repository URL, category **Dashboard** (a default-store submission for
Weather Neon Card is under review). Or use the **Open in HACS** buttons above.

Also in the family: [Neon Dual Thermometer](https://github.com/cerealkiller57540/neon-dual-thermo-card) ·
[Neon Entities](https://github.com/cerealkiller57540/neon-entities-card) ·
[Neon Markdown](https://github.com/cerealkiller57540/neon-markdown-card) ·
[Neon Header v2](https://github.com/cerealkiller57540/neon-header-card-v2)

## 🔌 Beyond cards: integrations

Not only UI — two full Home Assistant integrations for the Orange Livebox ecosystem:

- [**livebox-extended**](https://github.com/cerealkiller57540/livebox-extended) — the Livebox and its Wi-Fi 6 / Wi-Fi 7 repeaters, auto-discovered, over the local API.
- [**liveboxtv_ng**](https://github.com/cerealkiller57540/liveboxtv_ng) — Livebox TV UHD decoders: config flow, SSDP/DHCP discovery, UPnP volume/mute, live EPG, multi-box.

## 🏠 First contribution to Home Assistant Core

🎉 My first pull request merged into Home Assistant itself:
[**Fix Discogs random record sensor when release has no format description**](https://github.com/home-assistant/core/pull/186405)
(#186405), shipped in [Home Assistant 2026.10.2](https://www.home-assistant.io/blog/2026/10/07/release-202610/).

## 🎨 Theme snippets

Small add-ons for your theme rather than cards, in
[**neon-theme-snippets**](https://github.com/cerealkiller57540/neon-theme-snippets) —
a theme that follows you into Settings and Developer tools, falling katakana in
the sidebar, and more.

## 🐾 Support

If you enjoy these cards, please consider donating to **Quatre Pattes**, an
animal rescue organization.

[![Sauver des animaux](https://img.shields.io/badge/🐾%20Sauver%20des%20animaux-Faire%20un%20don-ff69b4?style=for-the-badge)](https://don.quatre-pattes.org/s/?_jtsuid=70083177244599792679303)

> 💛 No need to support me — just help the animals.

---

<div align="center">

**Built for Home Assistant** · MIT licensed · no telemetry, no cloud

</div>

[ha-badge]: https://img.shields.io/badge/Home%20Assistant-custom%20cards-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white
[ha-url]: https://www.home-assistant.io/
[hacs-badge]: https://img.shields.io/badge/HACS-compatible-41BDF5?style=for-the-badge
[hacs-url]: https://hacs.xyz
[license-badge]: https://img.shields.io/badge/license-MIT-green?style=for-the-badge
[license-url]: https://github.com/cerealkiller57540/Home-Assistant-Neon-Cards/blob/main/LICENSE
[core-badge]: https://img.shields.io/badge/Home%20Assistant%20Core-contributor-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white
[core-pr]: https://github.com/home-assistant/core/pull/186405
[hacs-btn]: https://my.home-assistant.io/badges/hacs_repository.svg
