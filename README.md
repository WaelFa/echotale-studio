# 🎙️ Echo Tale Studio

**Echo Tale Studio** is an open-source desktop application designed for anyone who wants to create immersive, multi-cast audio experiences. Whether you are an indie author, a tabletop gamer, or a storytelling enthusiast, Echo Tale provides the tools to turn text into a living performance.

---

## 🎭 The Echo Tale Approach
We believe storytelling is personal. Echo Tale offers two distinct paths to bring your script to life:

1.  **AI-Generated Performance:** Choose from a library of high-fidelity, diverse AI voices to play every role in your story.
2.  **The Hybrid Narrator (Voice Cloning):** Do the voice acting yourself, then use our local cloning engine to maintain perfect consistency, tone, and quality across the entire project. Record once, and let the AI handle the rest.

---

## ✨ Key Features

* **Multi-Cast Workflow:** Easily assign different voices to different characters within a single project.
* **Personal Voice Cloning:** Clone your own voice locally to act as the narrator or a specific character, ensuring an authentic human touch.
* **Local-First Privacy:** Powered by the **Voicebox** engine. Generate audio on your own hardware with no mandatory subscriptions or data tracking.
* **Hybrid Cloud (BYOK):** Want more power? Plug in your own API keys for ElevenLabs, OpenAI, or Play.ht to use premium cloud models directly within the studio.
* **Universal Accessibility:** Designed for everyone—from professional authors to hobbyists wanting to experiment with the future of audio.

---

## 🛠️ Built On
* **Core Engine:** Based on [Jamie Pine's Voicebox](https://github.com/jamiepine/voicebox).
* **Frontend:** React + Tailwind CSS.
* **Backend:** Tauri (Rust) + FastAPI (Python).
* **AI Models:** Qwen3-TTS / LuxTTS.

---

## 🚀 Getting Started

### Prerequisites
* **Node.js** (v18+)
* **Python** (3.10+)
* **Rust** (via [rustup](https://rustup.rs/))
* **FFmpeg** (required for audio processing)

### Installation
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/yourusername/echotale-studio.git](https://github.com/WaelFa/echotale-studio.git)
   cd echotale-studio
