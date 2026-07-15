
# 🤖 Sarcastic AI Code Reviewer

An interactive, dark-themed hacking terminal web application that uses open-source AI to review and mock HTML layouts. Built with semantic HTML, CSS, and vanilla client-side JavaScript.

![License](https://img.shields.io/badge/license-Apache2.0)

---

## 💡 How It Works

This application connects directly to the **Qwen/Qwen2.5-Coder-7B-Instruct** open-source LLM hosted on Hugging Face. When code is submitted:
1. It reads the raw HTML layout.
2. A strict system instruction acts as a filter forcing the AI into a "Sarcastic Senior Developer" persona.
3. If it detects highly-nested `<div>` soup, it roasts the user.
4. If it detects clean semantic markup (`<main>`, `<header>`, `<section>`), it praises them using dry, heavy sarcasm.

---

## 🚀 Features

*   **Zero Server Setup:** Runs 100% in the browser using public API endpoints.
*   **Hacker Aesthetic:** Designed with a futuristic dark-mode green and red terminal UI.
*   **Resilient Design:** Uses `try...catch...finally` execution handling to prevent interface freezes during high API traffic or network downtime.

---

## 📂 Project Structure

```text
├── index.html     # Semantic markup layout structure
├── style.css      # Custom dark hacker terminal styling
├── script.js      # Hugging Face inference integration logic
└── README.md      # Project documentation
