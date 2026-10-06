# GlassUI — A GlassMorphism Remake of `redz-library-v5`

GlassUI preserves the **exact public API and internal architecture** of `redz-library-v5` — theme tag system, `E()` element creator, `D:Draggable` lerp dragging, resizers, dialog system, notify groups, file persistence — while replacing the theme with a **GlassMorphism** visual language: translucent gradients, soft blurple accents, low-opacity strokes, larger corner radii, and smooth `Quint`/`Back` tweens.

## ✨ What's New vs. redz-v5

| Feature | redz-v5 | GlassUI |
|---|---|---|
| Theme | Darker only | Glass / Void / Frost |
| Background | Flat gradient | Glass gradient + optional image |
| Corner radius | 6–8px | 10–14px |
| Stroke opacity | 1.0 | ~0.2 (subtle rim light) |
| Notifications | Slide-in from right | **Bottom → top** slide |
| Floating restore icon | ❌ | ✅ Draggable, customizable |
| CheckBox | ❌ | ✅ |
| UpperTag (GitHub style) | ❌ | ✅ |
| MultiTab | ❌ | ✅ |
| Lucide icons | ❌ | ✅ |
| Custom background image | ❌ | ✅ |

All redz-v5 features still work identically: `MakeWindow`, `MakeTab`, `AddToggle`, `AddButton`, `AddSlider`, `AddDropdown`, `AddTextBox`, `AddParagraph`, `AddSection`, `AddDiscordInvite`, `Dialog`, `Notify`, `NewNotifyGroup`, `SetTheme`, `SetUIScale`, `ReadFile`, `WriteFile`, `SetFlag`, `GetFlag`, resizers, minimize/restore.

## 📦 Installation

```lua
local GlassUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/badalgamerz309-cyber/Luau-Library-UI/main/GlassUI"))()
