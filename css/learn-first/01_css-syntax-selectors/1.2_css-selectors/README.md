# 🎯 CSS Selectors — Foundations

## 📌 Overview

CSS selectors define **how CSS reaches HTML elements**.

Before learning properties, layouts, or responsiveness, it is essential to understand **how elements are targeted**.  
Selectors answer one critical question:

> **Which elements should receive this style?**

This section builds selector intuition so CSS feels **logical, predictable, and debuggable**.

---

## 🎯 Purpose

This section focuses on **CSS selectors only**, not styling creativity.

The goals are to:

- Understand different types of selectors
- Learn how selectors relate to HTML structure
- Predict which elements will be affected by a rule
- Avoid over-specific or fragile selectors

Selectors are the **decision-makers** of CSS.

---

## 📑 Core Selector Concepts

| **Concept**         | **Description**                                |
| ------------------- | ---------------------------------------------- |
| Element Selector    | Targets elements by tag name                   |
| Class Selector      | Targets elements with a class                  |
| ID Selector         | Targets a unique element                       |
| Grouping Selector   | Applies the same styles to multiple selectors  |
| Descendant Selector | Targets elements inside another element        |
| Child Selector      | Targets direct children only                   |
| Pseudo-class        | Targets elements based on state or interaction |

---

## 🧠 How Selectors Work

Selectors match elements based on:

- Tag names
- Attributes
- Relationships
- User interaction

A selector does **not style** anything by itself — it only **chooses** elements.  
Properties and values do the styling later.

---

## 📄 Folder Structure

02_css-selectors/
├── basic-selectors/
│   ├── element-selectors/
│   ├── class-selectors/
│   └── id-selectors/
├── grouping-combining/
│   ├── grouping-selectors/
│   ├── descendant-selectors/
│   └── child-selectors/
├── pseudo-basics/
│   ├── hover/
│   └── focus/
└── notes/
    └── selector-rules.md

Each folder focuses on **one selector type at a time**.

---

## ⚠️ Common Selector Mistakes

Avoid these early mistakes:

- Using IDs for styling
- Writing overly complex selectors
- Relying on element selectors for components
- Not understanding selector reach
- Styling without checking HTML structure

Selectors should be **clear, minimal, and intentional**.

---
## 📌 Summary

- CSS selectors decide **who gets styled**
- Good selectors are simple and predictable
- Understanding selectors prevents CSS confusion
- This section builds the foundation for all CSS styling

> **If styling feels random, your selectors are unclear.**

