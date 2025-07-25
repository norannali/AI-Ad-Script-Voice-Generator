# 🎬 AI Ad Script & Voice Generator

This project is an AI-powered tool that automatically generates short, engaging **social media ad scripts** and converts them into **realistic voiceovers**. Perfect for platforms like **TikTok**, **Instagram Reels**, or **YouTube Shorts**.

> 💡 Built with [DeepSeek LLM](https://huggingface.co/deepseek-ai) via [Ollama](https://ollama.com/), Microsoft’s Edge TTS, and Gradio UI.

---

## 🚀 Features

✅ Generate compelling video ad scripts using DeepSeek (1.5B)  
✅ Converts text into speech with Edge TTS (e.g., en-US-AriaNeural)  
✅ Interactive web UI using Gradio  
✅ Automatically splits long texts for smoother voice output  
✅ One-click Google Colab demo  
✅ Clean and structured outputs: Text + Audio

---

## 📸 Demo

![app-ui-demo](assets/demo-ui.png)

Listen to a sample output:  
[🔊 Sample Voice Output (MP3)](assets/sample-voice.mp3)

---

## 🔧 Technologies Used

| Component      | Purpose                            |
|----------------|------------------------------------|
| **Ollama**      | Local LLM backend for inference    |
| **DeepSeek 1.5B** | Language model to generate scripts |
| **Edge-TTS**     | Microsoft Text-to-Speech           |
| **Gradio**       | User interface                    |
| **Python (asyncio, regex)** | Script logic and cleaning |
| **pydub**        | Merge multiple audio segments     |

---

## 📦 Installation

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/ai-ad-script-voice-generator.git
cd ai-ad-script-voice-generator
