# 🗣️ Voice Assistant with TTS (Text-to-Speech)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1T427XjaU118VJEfiBlUc6oubthBGu6cL?usp=sharing)

---

## 🎯 Project Description

This project demonstrates the creation of a **voice assistant** that:
- takes text input from the user,
- converts it into speech using **Text-to-Speech (TTS)** technology,
- and plays the resulting audio file.

It uses **audio samples (`audio_50_azip`)** and **a JSON configuration file** (`eastern-amp-462308-h1-f9be26add265.json`) to integrate with the Google Cloud TTS API.

---

## 📦 Project Structure

```
📁 Voice_Assistant_TTS
├─ Копия_блокнота__Голосовой_помощник_с_TTS__.ipynb
├─ eastern-amp-462308-h1-f9be26add265.json
└─ audio_50_azip/
   ├─ *.wav / *.mp3 (generated audio files)
```

---

## ⚙️ Main Steps

1. **API Key Setup** — Load the JSON key and authenticate via Google Cloud.  
2. **Text Input** — Enter text manually or load from file.  
3. **Speech Generation** — Use Google TTS to synthesize the text into audio.  
4. **Playback or Save** — Output `.wav` or `.mp3` file.  
5. **Logging & Metadata** — Evaluate synthesis parameters and performance.

---

## 🔊 Result

In the Colab version, you can **listen to the generated voice samples directly in the notebook**.  
Each audio output corresponds to a text prompt, demonstrating different tone and speech rate.

---

## 🧩 Libraries Used

- `google.cloud.texttospeech`
- `pydub`
- `IPython.display.Audio`
- `os`, `json`, `time`

---

## 🧠 Project Evaluation

✅ Demonstrates the **full TTS workflow** — from authentication to synthesis and playback.  
✅ Implements **automated voice generation** with flexible settings (language, tone, speed).  
✅ Includes **real audio results**, which add strong presentation value.  

