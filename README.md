# ✝ FaithQuest — Family Bible Learning

**112 free Bible lessons for the whole family.** Age-adaptive, AI-powered, works offline.

🌐 **[Launch FaithQuest](https://dainantonio.github.io/FaithQuest/)** | 📱 **[Open App Directly](https://dainantonio.github.io/FaithQuest/app.html)**

---

## ✨ Features

| Feature | Description |
|---|---|
| 📖 **112 Lessons** | 16 learning paths covering core faith, parables, prayer, courage, and more |
| 🎄 **Seasonal Content** | Easter, Christmas, and Advent paths with timely lessons |
| 🎯 **Age-Adaptive** | Content adjusts for younger (4-6), kid (6-10), and teen (11-17) |
| 🤖 **AI Discussion** | Safe, age-appropriate FaithBot for deeper lesson exploration |
| 📴 **Offline Mode** | Lessons cached — use it anywhere without internet |
| 🔔 **Daily Reminders** | Push notifications to keep your family's streak going |
| 👶 **Multi-Child Profiles** | Each child gets their own avatar, progress, and journal |
| 📋 **Parent Guides** | Printable discussion guides for every lesson |
| 🔊 **Audio Narration** | Text-to-speech so younger kids can follow along |
| 🏆 **Badges & Streaks** | Gamification that makes learning fun |
| 🔖 **Bookmarks** | Save favorite lessons to revisit anytime |
| 🎉 **Celebrations** | Confetti animations when lessons are completed |

## 📚 Learning Paths

| Path | Lessons |
|---|---|
| 🌟 Core Lessons | 7 |
| 📖 Parables of Jesus | 7 |
| 🙏 Prayer & Stillness | 7 |
| ❤️ Kindness & Compassion | 7 |
| 🦁 Courage & Faith | 7 |
| 🌍 Creation & Science | 7 |
| 🤝 Friendship | 7 |
| 👨‍👩‍👧‍👦 Family | 7 |
| 🏛️ Old Testament Heroes | 7 |
| 👩‍🏫 Women of the Bible | 7 |
| 🧠 Wisdom & Decisions | 7 |
| 💜 Forgiveness & Grace | 7 |
| 🤲 Serving Others | 7 |
| 🐣 Easter Journey | 7 |
| 🎄 Christmas Story | 7 |
| 🕯️ Advent & Waiting | 7 |

## 🚀 Getting Started

### Use Online
Visit **[dainantonio.github.io/FaithQuest](https://dainantonio.github.io/FaithQuest/)** — no install needed!

### Install as App
1. Open the app in Chrome/Safari
2. Tap "Add to Home Screen" (or the install prompt)
3. FaithQuest appears as a native app on your device

### Run Locally
```bash
# Clone the repo
git clone https://github.com/dainantonio/FaithQuest.git
cd FaithQuest

# Serve locally
python -m http.server 5173
# or
npx serve .
```

## 🏗️ Architecture

- **Single-file app** (`app.html`) — no build step, no dependencies
- **External lesson data** (`lessons.json`) — easy to add/edit content
- **Firebase Auth** — Google sign-in + anonymous demo mode
- **Firestore** — progress sync across devices
- **Service Worker** — offline caching, push notifications
- **Web Speech API** — audio narration
- **Gemini AI** — age-safe lesson discussions

## 📄 License

MIT — free to use, modify, and share.
