# 🌿 Learn SQL with iKay

> An interactive, browser-based SQL e-learning app for beginners — built for young learners aged 11–13 as part of the **Learn With iKay** educational series.

![Learn With iKay](https://img.shields.io/badge/Learn%20With-iKay-1a5c34?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Beginner-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)
![HTML](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-orange?style=for-the-badge)

---

## 📖 About

**Learn SQL with iKay** is a single-file, self-contained web app that teaches PostgreSQL fundamentals through 15 interactive lessons. Each lesson includes syntax-highlighted code examples, a simulated SQL query runner, fun facts, and an instant-feedback quiz

No server. No installation. No internet required after the first load (fonts are fetched from Google Fonts on first open). Just open the HTML file and start learning.

---

## ✨ Features

- **15 Structured Lessons** — from simple arithmetic to JOINs, covering the full beginner curriculum
- **Simulated Query Runner** — students type SQL and see live table results without needing a real database
- **Instant Quiz Feedback** — 2 multiple-choice questions per lesson with correct/wrong highlighting and explanations
- **Progress Tracking** — header progress bar and sidebar checkmarks as lessons are completed
- **Celebration Screen** — trophy animation when all 15 lessons are finished
- **Zero Dependencies** — one `.html` file, works offline, no build step needed
- **Mobile Friendly** — responsive layout works on tablets and phones

---

## 📚 Lesson Curriculum

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | 🧮 SQL as a Calculator | `SELECT`, arithmetic operators |
| 2 | 🏷️ Data Types | `INTEGER`, `TEXT`, `BOOLEAN`, `NUMERIC`, `DATE`, `::` casting |
| 3 | 🏗️ CREATE TABLE | Table structure, column definitions |
| 4 | ✍️ INSERT INTO | Adding rows, multi-row inserts |
| 5 | 🔍 SELECT | Querying all or specific columns, `FROM` |
| 6 | 🎯 WHERE Clause | Filtering with `=`, `>`, `<`, `<>`, `>=` |
| 7 | 📊 ORDER BY | `ASC` and `DESC` sorting |
| 8 | ✏️ UPDATE | Modifying existing rows safely |
| 9 | 🗑️ DELETE | Removing rows, the importance of `WHERE` |
| 10 | 📈 Aggregation | `COUNT()`, `AVG()`, `MAX()`, `MIN()`, `SUM()` |
| 11 | 📦 GROUP BY | Grouping rows for summarised analytics |
| 12 | ✂️ LIMIT & OFFSET | Pagination, previewing data |
| 13 | 🏷️ Aliases (AS) | Renaming columns in results |
| 14 | 🔀 CASE Statement | Conditional logic, if-else in SQL |
| 15 | 🔗 JOINs | `INNER JOIN`, `ON`, combining two tables |

---

## 🚀 Getting Started

### Option 1 — Download and Open

1. Download `index.html`
2. Double-click to open in any modern browser (Chrome, Firefox, Edge, Safari)
3. That's it — no setup needed!

### Option 2 — Clone the Repo

```bash
git clone https://github.com/theikechukwu/intro2sql.git
cd intro2sql
open index.html   # macOS
# or
start index.html  # Windows
```

---

## 🗂️ Project Structure

```
learn-sql-ikay/
├── index.html   # The entire application (self-contained)
└── README.md            # This file
```

Everything — HTML, CSS, JavaScript, lesson content, quiz logic, and the Learn With iKay logo — is embedded in the single HTML file.

---

## 🛠️ How It Works

The app is built with vanilla HTML, CSS, and JavaScript — no frameworks or build tools.

- **Lesson data** is defined as a JavaScript array of objects, each containing the lesson content, code snippet, try-it prompt, a simulator function, and quiz questions.
- **The SQL simulator** uses regex pattern matching to parse common queries typed by students and returns a mock result table — giving a realistic feel without a real database backend.
- **Quiz logic** highlights correct/incorrect options and shows explanations inline.
- **Progress state** is stored in a JavaScript `Set` in memory (resets on page refresh — by design, keeping it simple for classroom use).

---


## 🙏 Acknowledgements

- Sample student data uses Nigerian names to reflect the target audience
- Lessons follow the curriculum from the **SQL for Data Analysis Beginners (PostgreSQL)** course by Learn With iKay
- Font: [Nunito](https://fonts.google.com/specimen/Nunito) and [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts

---

## 📄 Licence

This project is released for **educational use**. Feel free to adapt it for your own classroom or learning community with attribution.

---

<p align="center">Made with 💚 by <strong>Learn With iKay</strong></p>
