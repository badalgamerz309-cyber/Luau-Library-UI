<!-- ============================================================================ -->
<!--                              GLASS UI                                       -->
<!--                A GlassMorphism UI Library for Roblox                        -->
<!-- ============================================================================ -->

<div align="center">

# 🪟 GlassUI

### A modern, glassmorphic UI library for Roblox — rewritten from the classic `redz-library-v5`

[![Version](https://img.shields.io/badge/version-3.0.0-blue?style=for-the-badge)](https://github.com/badalgamerz309-cyber/Luau-Library-UI/releases/tag/v3.0.0)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](#-license)
[![Luau](https://img.shields.io/badge/language-Luau-purple?style=for-the-badge)](https://luau-lang.org/)
[![Platform](https://img.shields.io/badge/platform-Roblox-red?style=for-the-badge)](https://www.roblox.com/)
[![Status](https://img.shields.io/badge/status-stable-brightgreen?style=for-the-badge)](#-status)

*A translucent, blurred, animated UI library with the same API surface as redz-v5 —  
plus Checkbox, Keybind, ColorPicker, MultiTab, UpperTag, Lucide icons, floating minimizer, and more.*

</div>

---

## 📖 Table of Contents

- [Features](#-features)
- [Screenshots](#-screenshots)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Step-by-Step Tutorial](#-step-by-step-tutorial)
  - [1. Loading the Library](#1-loading-the-library)
  - [2. Creating a Window](#2-creating-a-window)
  - [3. Creating Tabs](#3-creating-tabs)
  - [4. Adding Sections & Paragraphs](#4-adding-sections--paragraphs)
  - [5. Buttons](#5-buttons)
  - [6. Toggles](#6-toggles)
  - [7. Checkboxes](#7-checkboxes)
  - [8. Sliders](#8-sliders)
  - [9. Dropdowns](#9-dropdowns)
  - [10. TextBoxes](#10-textboxes)
  - [11. Keybinds](#11-keybinds)
  - [12. Color Pickers](#12-color-pickers)
  - [13. Discord Invites](#13-discord-invites)
  - [14. Upper Tags](#14-upper-tags)
  - [15. Multi-Tabs](#15-multi-tabs)
  - [16. Notifications](#16-notifications)
  - [17. Dialogs](#17-dialogs)
  - [18. Theming](#18-theming)
  - [19. Config Save / Load](#19-config-save--load)
- [API Reference](#-api-reference)
- [Themes](#-themes)
- [Git Tags & Releases](#-git-tags--releases)
- [Changelog](#-changelog)
- [FAQ](#-faq)
- [License](#-license)
- [Credits](#-credits)

---

## ✨ Features

### Core
| Feature | Description |
|---|---|
| 🪟 **Draggable Window** | Smooth lerp-based dragging with idle watchdog |
| 📐 **Resizable Panels** | Two resizers: window size + tab panel width |
| 🗂 **Tabbed Interface** | Sidebar tabs with animated indicators |
| 🎈 **Floating Minimizer** | Draggable, customizable restore icon |
| 💾 **Persistent Config** | Auto-saves theme, size, and flags to disk |

### Components
| Component | Notes |
|---|---|
| 🔘 **Button** | With optional debounce/cooldown |
| 🎚 **Toggle** | Animated spring knob |
| ✅ **Checkbox** | GitHub-style with checkmark |
| 📊 **Slider** | Increment snapping + value pop animation |
| 📋 **Dropdown** | With built-in search bar |
| ⌨️ **Keybind** | Full KeyCode capture (Backspace = clear) |
| 🎨 **ColorPicker** | Color3 selector with swatch preview |
| 📝 **TextBox** | With focus highlight + text filter |
| 💬 **Paragraph** | Multi-line description |
| 📁 **Section** | Visual group separator |
| 🏷 **UpperTag** | GitHub-style colored tag pill |
| 🗂 **MultiTab** | Segmented button group |
| 📨 **Discord Invite** | Rich invite card with members count |
| 🔔 **Notification** | Bottom → top animated toast |
| 💭 **Dialog** | Modal with custom option buttons |

### Visual & UX
- **GlassMorphism** theme family: `Glass`, `Void`, `Frost`, `Aurora`
- Soft gradients, low-opacity strokes, rounded corners
- Bottom→top notification slide with auto-dismiss
- Lucide icon support (auto-fetched)
- Custom background image on the window
- Every interaction is tweened — no instant snaps

---

## 🖼 Screenshots

> *Add your screenshots here:*
> ```
> ![Window](docs/window.png)
> ![Notifications](docs/notifications.png)
> ![Dropdown](docs/dropdown.png)
> ```

---

## 📋 Requirements

| Requirement | Version |
|---|---|
| Roblox | Latest |
| Executor | Any (Synapse, Script-Ware, Krnl, Hydrogen, etc.) |
| Filesystem | Optional — enables persistence |

---

## 🚀 Installation

### Option 1 — Load via URL *(recommended)*

Copy this into your executor:

```lua
local GlassUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/badalgamerz309-cyber/Luau-Library-UI/main/GlassUI.lua"))()
