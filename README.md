# 🎶 StudyBuddy Music Bot – A YouTube-Powered Discord Bot  

## 📌 The Problem 
So there I was, studying on Discord with my friends, vibing to our YouTube playlist when—BAM! The Discord Music Bot we'd been using ran into yet another error. This wasn’t the first time in the past couple of weeks we’d run into this issue. Inviting a new bot didn’t help, troubleshooting didn’t help, and before we knew it—Discord music bots were practically useless. No more group study sessions with music. No more shared playlists. (We were divided between Spotify, YouTube Music & Apple Music).

It was a tragedy. 💔

But wait, you may be asking. **What even is Discord?** And well, if you’re new to Discord, think of it as Slack or Skype, but cooler. It’s a free, real-time chat and voice platform where you can create your own servers (communities) and talk with friends via text, voice, or video.

One of its best features? Voice Channels!

Unlike a regular phone or Zoom call, a Discord voice channel is an always-open chatroom where people can drop in and out whenever they want. You don’t have to call anyone—just join a channel and start talking! You can even have multiple voice chats running at once, making it perfect for gaming, studying, or just hanging out online.

For years, Discord users relied on music bots to stream YouTube or Spotify audio directly into a voice channel—turning Discord into a virtual study lounge or party room.
These bots worked by:
1. Joining your voice channel (as if they were another user).
2. Fetching music from YouTube or Spotify using APIs.
3. Streaming high-quality audio for everyone in the channel.

With a simple command like /play [song name], the bot would search YouTube, queue up the song, and play it—no screen-sharing, no extra setup. It was magic. ✨

Unfortunately, in late 2021, YouTube started shutting down major Discord music bots like Groovy and Rythm. 🚨 Spotify, meanwhile, never allowed direct streaming and required users to manually share links. This meant most Discord music bots stopped working overnight—leaving users scrambling for alternatives.

Since then, running a Discord music bot has become a constant battle against API limitations, takedowns, and technical workarounds. Many bots either:
- Break constantly due to streaming errors.
- Require complicated setups that casual users don’t want to deal with.
- Get shut down entirely because of legal issues.

And so, I had **two options**:  
1. **Complain about it.**  
2. **Build my own solution.** (Spoiler: I did this. ✨)  

Enter **StudyBuddy Music Bot (although me and my friends call it Daianna)**, a **Python-powered Discord bot** that **streams music from YouTube in real-time** so you can queue, play, pause, and skip songs—all inside a voice channel! 🎧💖  

---

## 🚀 What This Bot Can Do  
✅ **Play YouTube audio** directly in a Discord voice chat.  
✅ **Queue songs & manage playback** (play, pause, skip, stop).  
✅ **Support multiple users** in a voice channel.  
✅ **Stream high-quality audio** using **FFmpeg & YouTube API**.  
✅ **Fix what Discord broke** and bring **music back to study sessions.**  

---

## 🛠️ Technologies Used  
- **Python** – Core programming language.  
- **Nextcord** – An improved Discord API wrapper for Python.  
- **YouTube API** – Fetches and streams audio.  
- **FFmpeg** – Handles high-quality audio streaming.  
- **JSON** – Stores queue data and user preferences.  

---

## 📜 How It Works  
### **1️⃣ Join a Voice Channel**  
- Invite the bot using the `/join` command.  

### **2️⃣ Play a Song**  
- Type `/play [YouTube URL or search term]`.  
- The bot fetches the **best match** and starts streaming.  

### **3️⃣ Queue & Manage Playback**  
- `/queue` – Shows the current song queue.  
- `/skip` – Skips to the next song.  
- `/pause` – Pauses playback.  
- `/resume` – Resumes a paused song.  
- `/stop` – Ends playback & clears the queue.  

### **4️⃣ Keep Studying, Keep Vibing**  
- The bot stays in **sync with multiple users**, ensuring smooth music playback.  

---
## 🛠 🚀 Why This Matters
This project highlights my ability to:  
✔️ Develop scalable software solutions integrating APIs and real-time data processing.  
✔️ Architect full-stack applications using Python and asynchronous programming.  
✔️ Optimize system performance by implementing efficient data handling, caching, and queue management.  
✔️ Work with third-party APIs & SDKs, designing seamless integrations for user-facing applications.  
✔️ Apply software engineering best practices, including modular design, error handling, and logging.  

---

## 🔥 So, Why Does this Bot Exist?
- Because **studying without music is just sad.** 😭  
- But mainly because **coding is more fun when you build something that actually solves a problem—especially one that makes life easier (and way more fun) for you and your friends.**
---
### ⚠️ Disclaimer
This bot is intended for **personal and educational use only**.  
It uses the **YouTube API** to stream publicly available content but **does not host, download, or modify YouTube’s streams in any way**.  
Users are responsible for ensuring compliance with YouTube’s **Terms of Service** and Discord’s **API guidelines** when using this bot.

