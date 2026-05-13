# 🌱 Seedling Bob — Gamified Habit Tracker

https://cohortjuan.github.io/HabitTracker/

A gamified habit tracker built with **vanilla HTML, CSS, and JavaScript**.  
This project turns daily habits into an XP system where consistency levels up your digital companion — **Seedling Bob**.

Each completed habit contributes to XP, unlocking new levels and changing Bob’s visual mood as you progress.

---

## ✨ Features

- 🎯 Track daily habits (water, coding, exercise, etc.)
- ⚡ XP system based on completed habits
- 📈 Dynamic level progression system
- 🌱 Animated Seedling Bob with mood states
- 🧠 Random developer-themed motivational phrases
- 🔁 Undo completion for each habit
- 📊 Live XP progress bar
- 💾 Fully frontend (no backend required)

---

## 🧬 How It Works

- Each habit completion = 10 XP
- XP is calculated across all habits
- XP logic:
  - xp += Object.keys(habit.log).length * 10
- Level logic:
  - Level = Math.floor(XP / 50) + 1

---

## 📈 Level Progression

- Level 1–2 → Seedling 🌱
- Level 3–5 → Sprout 🌿
- Level 6+ → Overgrown Dev 🔥

Bob evolves visually based on your consistency.

---

## 📁 Project Structure

- index.html

Everything is included in a single file:
- HTML → structure (habits + Bob UI)
- CSS → styling, animations, mood states
- JavaScript → XP system + habit logic

---

## 🚀 How to Run

- Open directly in your browser:
  - open index.html

- Or use a local server:
  - npx serve

---

## 🧠 Core Logic Overview

### Habit Tracking

- Each habit stores daily completion logs:
  - log = { "2026-05-12": true }

---

### XP Calculation

- XP is based on completed habit entries:
  - xp = Object.keys(habit.log).length * 10

---

### UI Updates

- XP bar fills based on progress to next level
- Level text updates dynamically
- Seedling Bob changes mood based on level:
  - Neutral → early stage
  - Happy → mid progression
  - Elite → high-level dev mode

---

## 💡 Future Improvements

- 💾 Save progress with LocalStorage
- 📅 Calendar-based streak tracking
- 🏆 Achievement / badge system
- 🔔 Daily reminders
- 📊 Analytics dashboard (streaks, consistency rate)
- 👤 Multiple habit profiles

---

## 🎨 Design Philosophy

This project treats habits like a progression system in a game:

“Consistency is XP. Discipline is leveling up.”

It blends:

- Productivity × Gamification
- Minimal UI × Emotional feedback
- Developer humor × Self-improvement

---

## 📸 Screenshot

-<img width="882" height="1319" alt="image" src="https://github.com/user-attachments/assets/c856e7b7-468e-4d57-98ef-236e4a5bb292" />


---

## 📜 License

- This project is open-source and free to use under the MIT License
