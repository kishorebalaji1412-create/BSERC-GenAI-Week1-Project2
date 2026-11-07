# BSERC GenAI Internship — Week 1 Project 2: Thinking in HTML

This repository contains my submission for **Project 2 (Thinking in HTML)** of the Bharat Space Education Research Centre (BSERC) GenAI Internship.

The objective of this project is to use AI prompting tools to build fully interactive, single-file HTML web applications containing rich UI controls (such as sliders, filters, flip cards, and quizzes) without manually writing code.

---

## 📁 Repository Structure

* **`page1.html` — Exam Prep & Revision Dashboard**
  * **Target Audience:** Engineering student preparing for exams.
  * **Key Features:** Interactive machine learning quiz with real-time scoring, topic completion checklist with progress tracking, exam countdown timer, flip-card flashcard revision deck, and dark/light theme toggle.
* **`page2.html` — Personal Money & Expense Explorer**
  * **Target Audience:** Personal finance management and budget tracking.
  * **Key Features:** Dynamic budget sliders updating monthly balances live, category filter buttons (Food, Tech, Travel, Subscriptions), alert modal to inspect duplicate transactions, breakdown visual charts, and a quick reset option.
* **`page3.html` — Tech Stack Decision Helper Matrix**
  * **Target Audience:** Developers evaluating backend technologies (e.g., Supabase vs Firebase vs PostgreSQL).
  * **Key Features:** Real-time weighting sliders for criteria (Cost, Speed, Scalability, Ease of Use) that automatically re-rank choices live, searchable criteria table, dynamic recommendation badge, and interactive column highlights.
* **`prompts.txt` — Prompt Engineering Log**
  * Ordered log containing all system prompts and iterative refine commands used across ChatGPT, Claude, and Gemini to generate the HTML pages.

---

## ⚡ Technical Highlights

- **Single-File Architecture:** Built as self-contained `.html` files combining HTML markup, CSS styling, and JavaScript logic with zero external server dependencies.
- **Rich Interactivity:** Every page includes 5+ click, slide, or filter controls.
- **Fully Responsive:** Styled to render seamlessly on both mobile screens and desktop devices.
- **Offline Capable:** Runs locally in any web browser without requiring an active internet connection or backend API.

---

## 💻 How to Run

1. Clone or download this repository to your computer.
2. Double-click any `.html` file (`page1.html`, `page2.html`, or `page3.html`) to open and test it directly in your web browser.
