# 🎲 React Dice Game – Assignment

It's time to roll the dice — literally.

This Week 4 assignment will help you apply everything you've learned about **React** so far. You'll build a small but fun game that involves number picking, random chance, score tracking, and a bit of luck (but mostly logic).

---

## 📝 Problem Statement

Build a **React-based dice game** that lets users:
- Select a number between 1 and 6
- Roll a dice
- Gain or lose points based on the result

Yes, it's like gambling — but educational.

---

## 📋 Game Rules

- Select a number between 1–6 before rolling.
- On clicking **"Roll Dice"**, a dice face appears randomly.
- If your selection **matches** the dice roll:
  - You score **+N points** (N = selected number)
- If it doesn't:
  - You lose **2 points**
- Include a **Reset Score** button
- Show an **error** if the user tries to roll without selecting a number
- Add a button to **toggle the rules** (because we all forget them)

---

## 🛠 Required Features

-  Number selection (1–6) with clear visual feedback
-  Random dice roll (with dice face image)
-  Score updates in real-time
-  Reset score functionality
-  Toggle to show/hide rules
-  Error handling for missing number selection
-  Responsive layout that works on all screens

---

## 🧩 Suggested Components

- `App`: Manages global game state and navigation
- `Home`: A simple landing page with a start button and a friendly dice image
- `Game`: Core gameplay — number selection, dice roll, score logic
- `Box`: For rendering selectable numbers (1–6)
- `Button`: A reusable component for all clickable buttons

---

## 🧑‍💻 Tech Stack

- **React.js** (v18+)
- **Functional Components**
- **Hooks** (`useState`, `useContext`)
- **React Context API** (to share state globally)
- **CSS Modules** or any styling approach you're comfortable with

---

## 📅 Submission Details

- **Deadline:** 2nd July, 11:59 PM
- **Submit here:** [Assignment Submission Form](https://forms.gle/G8tTKS1ukG9F21Km8)

---

## 💡 Tips

- Don't overthink — start small and test your logic.
- Make sure your score logic is solid before styling it pretty.
- Use [React Docs](https://react.dev/learn) if something doesn’t make sense (which is normal).
- And no, you don’t have to actually shake your laptop to roll the dice — just click a button.

---

Good luck — may the odds (and the dice) be in your favor!
