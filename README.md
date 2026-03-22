# 🥧 PI-Setup

> The hardest part of edge AI isn't the AI — it's getting the hardware ready. Here's how it's done.

---

## 🧠 About This Project

**PI-Setup** documents the full process of setting up a Raspberry Pi 5 as an edge AI device — installing dependencies, configuring Ollama, downloading local models, and proving the whole thing works offline.

It took a lot of downloading, a lot of connecting, and a lot of patience. But it was worth it.

---

## ✅ Proof It Works

Asked the Pi — with no internet connection — *"Who was the first person to walk on the moon?"*

The Pi answered in **5 seconds**:

> *"The first person to walk on the moon was Neil Armstrong. On July 20, 1969, Armstrong and Edwin 'Buzz' Aldrin became the first humans to set foot on the lunar surface during NASA's Apollo 11 mission."*

No Wi-Fi. No API. No cloud. Just the Pi, thinking on its own.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| **Hardware** | Raspberry Pi 5 |
| **Local AI Runtime** | Ollama |
| **Model** | Llama / Gemma |
| **AI Assist** | Claude (Anthropic), Gemini (Google) |
| **Language** | Python |

---

## ⚙️ What the Setup Involved

- Flashing the Raspberry Pi OS onto an SD card
- Connecting the Pi to power, display, keyboard, and camera
- Installing Python and required dependencies
- Downloading and configuring Ollama on the Pi
- Pulling a local LLM (Llama/Gemma) onto the device
- Testing the model offline to confirm everything works

---

## ⏱️ Performance

| Query | Response Time | Internet Used |
|---|---|---|
| "Who was the first person to walk on the moon?" | ~5 seconds | ❌ None |

---

## 💡 Key Learnings

- Setting up a Raspberry Pi from scratch is non-trivial but totally doable
- Ollama makes running local LLMs on low-power hardware surprisingly accessible
- Edge AI is real — a Pi can answer complex questions with zero internet dependency
- The setup process is a one-time cost; once it's done, it unlocks every Pi project that follows

---

## 🚀 Part of the AI Bootcamp

This setup was the foundation for all Week 2 Physical AI projects in the 15-day AI Developer Bootcamp.  
See the full bootcamp repo → [The AI Bootcamp](../README.md)

---

*Difficult to set up. Worth every second.* 🔧
