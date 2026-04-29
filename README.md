# 🧮 Math Master – Adaptive Math Quiz

A fully functional, browser-based MCQ quiz application for math practice.  
No backend, no database – everything runs locally in your browser.

![Math Quiz Interface](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Demo [Math Master Demo](https://mathquiz.ouchh.com)

## ✨ Features

- **5 Quiz Categories** – Arithmetic, Fractions, Symmetry, Probability, Word Problems
- **Class Level Selection** (1 to 10) – difficulty scales logically
- **Randomly Generated Questions** – no repetition within a session
- **60‑Second Timer** per question – auto-mark with solution on timeout
- **Instant Feedback** – shows correct answer and **detailed step‑by‑step solution** (teacher‑style)
- **Live Scoreboard** – attempts, marks, percentage, class level, total time spent
- **Symmetry Diagrams** – visual SVG illustrations for symmetry questions
- **Mobile‑First Responsive** – works on desktop, tablet, and mobile
- **Clean Modern UI** – smooth animations and transitions

## 🚀 How to Use

1. **Clone or download** this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Select a **category** (e.g., Arithmetic, Fractions).
4. Choose a **class level** (1–10).
5. Start the quiz – answer each question within 60 seconds.
6. After each answer, read the **detailed solution** and click **Next**.
7. End the quiz anytime to see your final result.

No internet connection needed after download.

## 🛠️ Tech Stack

- **HTML5** – structure
- **CSS3** – responsive design, animations, Flexbox/Grid
- **Vanilla JavaScript** – all logic, question generation, state management

## 📂 Project Structure
math-master-quiz/
├── index.html (single file containing everything)
└── README.md (this file)



## 🧠 Question Generation

All questions are generated **dynamically** using JavaScript.  
Each category has its own generator that respects the selected class level.  
A unique hashing system prevents question repetition within a single quiz session.

### Example Solutions (Teacher‑Style)

- **Probability:**  
  *Step 1: Identify favourable outcomes. Step 2: Count total outcomes. Step 3: Write fraction. Step 4: Simplify.*

- **Word Problems:**  
  *Step‑by‑step reasoning, formula application, and final calculation.*

- **Symmetry:**  
  *Explanation of lines of symmetry + visual SVG diagram.*

## 📱 Responsive Design

The layout adapts seamlessly to:
- Desktop (≥1024px)
- Tablet (768px – 1024px)
- Mobile (≤640px) – stacked score bar, larger touch targets.

## 🔧 Customization

You can easily:
- Add more categories to the `Generators` object.
- Adjust timer duration (default 60s) in `loadQuestionUI()`.
- Modify difficulty scaling inside each generator.

## 📄 License

MIT – free to use, modify, and distribute.

## 🙌 Acknowledgements

Built as a pure front‑end project to demonstrate advanced JavaScript, dynamic UI, and mathematical pedagogy.

**Enjoy practicing math!** 🎯
