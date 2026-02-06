# 🎵 AI Telegram Playlist Bot

An **AI-powered Telegram bot** that generates personalized music playlists using **Generative AI** and **Spotify**, delivered instantly to users on Telegram. The bot understands user prompts (mood, genre, artist, language, vibe) and returns a curated playlist in a clean, readable format.

---

## 🚀 Features

* 🤖 **AI Playlist Generation** using Google Gemini Chat Model
* 💬 **Telegram Bot Integration** for user interaction
* 🎧 **Spotify Playlist Search** (songs, playlists, artists)
* 🧠 **Conversation Memory** for contextual responses
* 🛠️ **Automated Workflow** (trigger → AI → Spotify → Telegram)
* ✨ Clean and formatted playlist output

---

## 🧩 Workflow Overview


The bot is built as an **automated workflow pipeline**:

1. **Telegram Trigger**

   * Listens for user messages (e.g., "Top 10 sad Hindi songs")

2. **Workflow Configuration**

   * Validates input and prepares prompt for AI

3. **Playlist Generator (AI Agent)**

   * Uses **Google Gemini Chat Model** to understand intent
   * Maintains **conversation memory** for better recommendations
   * Calls **Spotify Tool** to search playlists/songs

4. **Format Playlist Message**

   * Structures playlist name, tracks, and links

5. **Send Playlist to Telegram**

   * Sends final response back to the user in Telegram

---

## 🛠️ Tech Stack

* **Telegram Bot API** – User interaction
* **Google Gemini Chat Model** – AI playlist generation
* **Spotify API** – Music & playlist search
* **Workflow Automation Tool** (visual pipeline)
* **Conversation Memory** – Context-aware responses

---

## 📸 Workflow Screenshot

> Below is the visual workflow used to build the bot:

<img width="1401" height="601" alt="Screenshot 2026-01-28 121313" src="https://github.com/user-attachments/assets/7518a9c1-64a7-4b87-9120-e5be063d524a" />




---

## 🧪 Example Usage

**User Input (Telegram):**

```
Give me a top 10 workout playlist
```

**Bot Output:**

```
🎧 Workout Energy Playlist
1. Song Name – Artist
2. Song Name – Artist
...
🔗 Spotify Playlist Link
```

---



