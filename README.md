# Habit Tracker 🌱

A simple, atmospheric habit tracker built with vanilla HTML, CSS, and JavaScript. Each habit grows visually over time using a plant-based streak system.

## Live Demo[
https://cohortjuan.github.io/HabitTracker/

## Features

- Clean, minimalist UI with a dark botanical aesthetic
- Click-anywhere habit toggling (label-based UX)
- Persistent state using `localStorage`
- Streak tracking per habit
- Visual growth system:
  - 🌰 Seed (0–2 days)
  - 🌱 Sprout (3+ days)
  - 🌿 Leaves (7+ days)
  - 🌷 Flower (14+ days)
  - 🌳 Tree (30+ days)
- Simple breathing exercise tool (box breathing)
- No frameworks, no dependencies

## Tech Stack

- HTML5 (semantic structure)
- CSS3 (custom styling, flexbox, animations)
- JavaScript (DOM manipulation, localStorage)

## How It Works

Each habit stores:
- completion state
- streak count

When a checkbox is toggled:
- streak increases if checked
- resets if unchecked
- plant emoji updates based on streak milestones

Data is saved automatically in the browser using `localStorage`.

## Future Improvements

- Daily reset system (true “day tracking”)
- Streak protection mechanics
- Calendar view of completions
- Animated plant growth transitions
- Dark/light theme toggle
- Habit creation and deletion UI

## What I Learned

- Structuring semantic HTML for interactive UI
- Using `label` elements for accessible click behavior
- Managing persistent state with `localStorage`
- Designing simple game-like feedback loops in UI
- Building a small feature system without frameworks

## Screenshot

<img width="1269" height="846" alt="image" src="https://github.com/user-attachments/assets/7ff613f7-77eb-41fb-a6d6-254b565c1ffa" />


## License

Free to use for learning and personal projects.
