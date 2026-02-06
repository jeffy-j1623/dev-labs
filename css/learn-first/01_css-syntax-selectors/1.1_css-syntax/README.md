# 🎯 CSS Syntax — Foundations

## 📌 Overview

This section focuses **only on CSS syntax** — the *grammar of CSS*.

Before learning how CSS selects elements or styles layouts, it is critical to understand **how CSS rules are written** and **why they sometimes fail silently**.

CSS syntax errors don’t always throw visible errors, so a strong syntax foundation saves **hours of debugging later**.

This folder exists to make CSS feel **strict, logical, and predictable**.

---

## 🧠 What Is CSS Syntax?

CSS syntax defines the **structure of a CSS rule** — how the browser reads and interprets styling instructions.

Every valid CSS rule is built from:

- A selector
- A declaration block
- One or more property–value pairs

If syntax is wrong, the browser may:
- Ignore a single declaration
- Ignore the entire rule
- Ignore the entire stylesheet

Understanding syntax prevents these silent failures.

---

## 📄 Files in This Folder
~~~
01_css-syntax/
├── index.html → Minimal HTML for testing syntax
├── style.css → Syntax-focused CSS rules
├── README.md → Concept explanation + rules
└── notes/
     ├── syntax-rules.md
     ├── common-syntax-errors.md
     └── debugging-tips.md
~~~

## ⚠️ Common Syntax Mistakes

Watch out for:

- Missing semicolons
- Misspelled properties
- Invalid values for a property
- Missing closing braces
- Writing CSS inside HTML incorrectly

These mistakes are **silent killers** in CSS.

## 🧾 Summary

- CSS syntax is the **grammar of CSS**
- Browsers fail silently on syntax errors
- Strong syntax knowledge prevents confusion later
- This folder builds confidence and debugging skill

> **If CSS breaks, check syntax first — always.**

🚀 *Syntax mastered → selectors make sense → layouts become easy.*