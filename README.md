<div align="center">

# StudioBridge (Proposal)🎨⚙️
**Logitech MX Plugin for CSP: Bringing API-Less Tactile Control to Digital Artists**

[![Logitech Actions SDK](https://img.shields.io/badge/Logitech_Actions_SDK-Node.js-blue.svg)](https://devstudio.logitech.com/)
[![Target App](https://img.shields.io/badge/Target-Clip_Studio_Paint-000000.svg)](https://www.clipstudio.net/en/)
[![Status](https://img.shields.io/badge/Status-Hackathon_Proposal-brightgreen.svg)]()

</div>

StudioBridge is an intelligent, API-less "Desktop Agent" designed to connect Logitech’s premium MX hardware directly to Clip Studio Paint (CSP). By utilizing the Logitech Node.js SDK and native OS-level UI automation, this plugin transforms deeply nested digital menus into intuitive, physical muscle memory.

---

## 📖 The Problem & Solution
Clip Studio Paint is the global industry standard for webtoon, manga, and 2D illustration. However, its official developer SDK is locked entirely to the Japanese region. Global artists are left with zero API-level hardware integrations, forcing them into a repetitive cycle of keyboard shortcuts and menu-diving that disrupts creative flow.

**StudioBridge** bypasses the need for an official software API. It maps physical hardware inputs natively to OS-level UI commands, providing a seamless, highly secure, and tactile drawing experience.

---

## ✨ Core Features & Hardware Integration

* 🎛️ **The Visual Auto Action Deck (MX Keypad)**
  The keypad’s 9 LCD screens act as a dynamic management board. Trigger complex CSP *Auto Actions* with a single physical press—instantly generate comic panels, apply screen tones, or organize layer blending modes without opening a side menu.
* 🔄 **Analog Canvas Control (MX Dialpad)**
  The frictionless aluminum dial is mapped to step-free canvas rotation, allowing artists to smoothly angle the artboard to match natural wrist movements. The vertical roller dynamically adjusts brush radius mid-stroke.
* 🎯 **Contextual Tooling (Actions Ring & MX Master 4)**
  Clicking the MX Master 4 gesture button opens the virtual Actions Ring exactly at the stylus or cursor location. The ring dynamically populates with specific sub-tools (e.g., swapping from a G-Pen to a watercolor blender).
* ⚡ **Vector Haptic Feedback (MX Master 4)**
  Utilizing the mouse's haptic engine, the plugin delivers a subtle physical pulse when vector lines seamlessly intersect or lock onto a perspective ruler, giving physical confirmation of drafting accuracy.

---

## 🏗️ Technical Architecture & Philosophy

* **Week 1 (Foundation):** Establish connection via the Logitech Node SDK; initialize the repository structure.
* **Week 2 (The UI Bridge):** Integrate `nut.js` to locate the active software window and successfully pass test keystrokes to CSP.
* **Week 3 (Hardware Mapping):** Map Dialpad rotation to canvas adjustments; bind CSP internal Auto Actions to the MX Keypad LCD screens.
* **Week 4 (Polish & Haptics):** Finalize MX Master 4 vector haptics and Actions Ring JSON configurations; conduct final code refactoring.

---

## 👨‍💻 About the Developer
**John Lloyd D. Cañoy** *Information Technology Undergraduate | University of Science and Technology of Southern Philippines (USTP)*

Passionate about bridging the gap between physical hardware and digital creative workflows. 

---
*Developed for the Logitech DevStudio Challenge.*