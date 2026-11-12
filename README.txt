# 🦐 KRILLION — Deep-Sea Rarity Trivia

**Think Obscure. Sink Deeper.**

![HTML5](https://img.shields.io/badge/HTML5-Single--File-0284c7?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38bdf8?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-Structured_JSON-a855f7?style=for-the-badge&logo=googlegemini&logoColor=white)
![Zero Build](https://img.shields.io/badge/Build-Zero_Dependencies-10b981?style=for-the-badge)

**Krillion** is a client-side, AI-judged reverse-trivia game where obvious answers barely break the surface. Outsmart the crowd with valid yet ultra-obscure pulls across **7 prompts** to sink your krill from the sunlit surface all the way down to the **7,000m Hadal Trench**.

---

## 🌊 How It Works

1. **7 Open-Ended Prompts:** Dive across *Geography, Science, Pop Culture, History, Nature, Food & Drink,* and *Wordplay*.
2. **25-Second Oxygen Clock:** Race the timer to submit a valid real-world answer. Wrong guesses don't end your round—the clock keeps ticking so you can pivot and dive again.
3. **Live AI Rarity Judging:** Google Gemini verifies your answer via **Structured JSON Output** (`responseSchema`), scores its obscurity from **1 to 100**, roasts or praises your pull, and reveals **3 ultra-rare (90+ pt) pulls** you could have used.
4. **1 Point = 10 Meters:** Every rarity point sinks your submersible 10 meters deeper, dynamically shifting the ocean lighting, sunrays, and bioluminescence around you.

---

## 🦑 Rarity Tiers & Bathymetric Zones

### Answer Rarity Tiers
| Score | Depth Gained | Tier | Description |
| :--- | :--- | :--- | :--- |
| **0 pts** | `+0m` | 💨 **Surface Drift** | Ran out of oxygen before locking in a valid answer |
| **1 – 15 pts** | `+10m – 150m` | 🦠 **Plankton** | The top 1–3 most obvious answers everyone says immediately |
| **16 – 35 pts** | `+160m – 350m` | 🐟 **Schooling Fish** | Common answers or classic "I'm being clever" traps |
| **36 – 60 pts** | `+360m – 600m` | 🐠 **Reef Dweller** | Solid, moderately well-known pull |
| **61 – 80 pts** | `+610m – 800m` | 🐙 **Deep Diver** | Impressive answer requiring genuine topic familiarity |
| **81 – 94 pts** | `+810m – 940m` | 🦑 **Abyssal** | Deep cut few players would recall under a 25s clock |
| **95 – 100 pts** | `+950m – 1,000m` | 🦐 **One in a Krillion** | Legendary, ultra-obscure, 100% legitimate pull |

### Ocean Depth Zones
* **0m – 999m:** ☀️ *Epipelagic (Sunlight Zone)*
* **1,000m – 2,999m:** 🌗 *Mesopelagic (Twilight Zone)*
* **3,000m – 4,499m:** 🌑 *Bathypelagic (Midnight Zone)*
* **4,500m – 5,999m:** 🔮 *Abyssopelagic (Abyssal Zone)*
* **6,000m – 7,000m:** 🦑 *Hadalpelagic (Hadal Trench)*

---

## ✨ Features

* **Three Prompt Deck Modes:**
  * ✨ **Fresh AI-Generated Dive:** Generates 7 brand-new prompts on the fly.
  * 🎲 **Curated + AI Hybrid:** Mixes hand-crafted prompts with fresh AI wildcards.
  * ⚡ **Instant Built-In Deck:** Launches immediately with curated prompts while Gemini judges your answers.
* **Model Flexibility:** Built-in support for `gemini-3.8-flash`, `gemini-3.5-flash-lite`, `gemini-4-argon`, `gemini-4-carbon`, or any custom model ID.
* **Latency-Fair Timer:** The 25-second countdown automatically pauses while waiting on API evaluation so network latency never costs you oxygen.
* **Shareable Dive Logs:** Copy a color-coded emoji summary of your 7-round descent and final Diver Rank (`🦠 Surface Plankton` up to `👑 Leviathan of the Hadal Trench`) to your clipboard in one click.

---

## 🚀 Quick Start

No bundler, Node.js installation, or backend server required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Joshua1111112222/Krillion.git](https://github.com/Joshua1111112222/Krillion.git)
   cd Krillion
