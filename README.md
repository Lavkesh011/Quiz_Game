# 🧠 Interactive Web Development Quiz Game

A clean, modern, and interactive Quiz Game built using vanilla **HTML5**, **CSS3**, and **JavaScript (ES6)**. This web application tests the user's core web development skills with dynamic multiple-choice questions, interactive styling, and real-time score tracking.

---

## 📷 Preview

Here is a visual mockup of the application interface:

![Quiz Game Interface Preview](./assets/quiz_game_preview.png)

---

## ✨ Features

- **Dynamic Question Loading**: Questions, option choices, and indexes are populated dynamically using JavaScript.
- **Interactive UI**: Custom radio buttons with clear text alignments, hover transitions on the submission button, and smooth layout styling.
- **Score Calculation**: Automatically calculates and displays the user's final score (`Correct Answers / Total Questions`) in a clean result view upon quiz completion.
- **Modern Typography**: Styled using Google Font's **Poppins** typeface for excellent readability and aesthetic appeal.
- **Responsive Layout**: Designed with relative units (`rem`, `%`) to remain responsive on varying screen sizes.

---

## 📂 Project Architecture

The project has a simple, modular structure containing the following files:

```bash
Quiz_Game/
├── assets/
│   └── quiz_game_preview.png  # Application screenshot preview
├── index.html                 # Core skeleton structure
├── index.css                  # Responsive layouts and visual styling
├── index.js                   # Application logic, scoring, and question data
└── README.md                  # Project documentation (this file)
```

### File Responsibilities:
- **[index.html](file:///c:/Users/lavke/Documents/ProjectsOnGithub/Quiz_Game/index.html)**: Sets up the main container, option inputs, labels, and script/stylesheet linkages.
- **[index.css](file:///c:/Users/lavke/Documents/ProjectsOnGithub/Quiz_Game/index.css)**: Applies modern aesthetics, handles alignment, adds border-radius cards, drops shadow effects, and styles hover states on the submit button.
- **[index.js](file:///c:/Users/lavke/Documents/ProjectsOnGithub/Quiz_Game/index.js)**: Stores the quiz questions dataset, manages index state, updates UI contents dynamically on submit, and resets radio states on question change.

---

## 🛠️ Tech Stack

- **HTML5**: Structured semantic components.
- **CSS3 (Vanilla)**: Flexbox layout, Google Fonts integration, and interactive transitions.
- **JavaScript (ES6+)**: Document Object Model (DOM) manipulation, event listeners, state tracking, and ES6 array helpers.

---

## 🚀 Getting Started

To run this project locally, you don't need any complex installation or compilation steps. Just follow these instructions:

### 1. Clone the Repository
```bash
git clone https://github.com/Lavkesh011/Quiz_Game.git
cd Quiz_Game
```

### 2. Run the Application
Simply double-click the `index.html` file in your file explorer, or run it using a local development server like VS Code's Live Server or Python's HTTP server:

Using python:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your favorite browser.

---

## ✍️ Customizing Questions

You can easily add or edit quiz questions by modifying the `quizData` array in **[index.js](file:///c:/Users/lavke/Documents/ProjectsOnGithub/Quiz_Game/index.js)**:

```javascript
const quizData = [
    {
        question: "Your custom question here?",
        a: "Option A",
        b: "Option B",
        c: "Option C",
        d: "Option D",
        correct: "a", // The correct option key ('a', 'b', 'c', or 'd')
    },
    // Add more question objects as needed...
];
```

---

## 🔮 Future Enhancements (Roadmap)

To elevate this project further, the following features could be added:
1. **Timer countdown**: A visual progress bar or countdown timer (e.g., 15 seconds per question).
2. **Dynamic Categories**: Integration with an external API (like Open Trivia DB) to fetch questions from various domains.
3. **Sound Effects**: Audio feedback on correct and incorrect selections.
4. **Leaderboard & Local Storage**: Save player name and scores to local storage to display a high-score board.
