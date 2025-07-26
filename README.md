![AI Twitter Bot](https://github.com/abu-sinan/ai-twitter-bot/blob/main/assets%2Ffile_00000000460461f7adb170100d87e54b.png)
# 🤖 AI Twitter (X) Bot (Gemini + Zapier + Buffer)

This bot posts AI-generated tweets every 12 hours using **Gemini 2.0 Flash**, **Zapier**, and **Buffer**. It randomly picks a topic, asks Gemini to write a tweet, and adds it to your Buffer queue.

---

## 🧱 Tech Stack

- 🔮 Gemini 2.0 Flash (for tweet generation)
- ⚡ Zapier (workflow automation)
- 📦 Buffer (tweet scheduling)

---

## 🗂️ Folder Guide

| File/Folder              | Description                                  |
|--------------------------|----------------------------------------------|
| `prompts/prompt_template.txt` | Prompt used to generate tweet via Gemini |
| `data/topics.txt`        | List of tweet topics                        |
| `zapier/zap_config.md`   | Step-by-step Zapier setup                   |
| `.gitignore`             | Git ignore rules                           |
| `LICENSE`                | MIT License                                 |

---

## 🕒 Schedule

Tweets are generated and scheduled **every 12 hours** using Zapier. Buffer handles the posting at your preferred times (e.g., 10AM & 10PM).

---

## 📌 Example Topics

- Python scripting
- Automation tips
- Bot development
- Chatbot techniques
- Artificial Intelligence tools

[See full list](https://github.com/abu-sinan/ai-twitter-bot/blob/main/data/topics.txt)

---

## 📑 License

[MIT](https://github.com/abu-sinan/ai-twitter-bot/blob/main/LICENSE)