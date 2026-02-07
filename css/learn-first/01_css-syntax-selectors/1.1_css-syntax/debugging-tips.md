# 🛠️ CSS Debugging Tips

## 🎯 Purpose

This document is a **practical playbook** for debugging CSS.

When CSS doesn’t work, the problem is usually **not logic or layout** — it’s:

- Syntax mistakes
- Incorrect selectors
- Browser interpretation issues

This guide tells you **what to check, in what order**, so you don’t guess.

---

## 🧠 Golden Rule of CSS Debugging

> **Assume CSS is correct — assume your syntax or selector is wrong.**

Browsers do not throw errors for CSS failures.  
They silently ignore what they don’t understand.

---

## 🔍 Step-by-Step Debugging Checklist

Follow this order **every time**.

---

### ✅ Step 1: Confirm CSS File Is Loaded

Check:

- Correct file path in HTML
- File name spelling and casing
- CSS file actually exists

If CSS is not loaded:

- Nothing else matters

---

### ✅ Step 2: Check Syntax First (Always)

Before touching selectors or values, check:

- `{ }` braces are balanced
- Every declaration ends with `;`
- Every property has a `:`
- Comments are properly closed

🧠 90% of early CSS bugs live here.

---

### ✅ Step 3: Check Selector Targeting

Ask:

- Does this selector match any element?
- Is it too specific?
- Is it targeting more than expected?

Use browser inspection tools to verify matches.

---

### ✅ Step 4: Inspect the Element (Critical Skill)

Use browser DevTools to:

- Select the element
- View applied styles
- See crossed-out rules
- Identify overridden declarations

Crossed-out CSS = rule is valid but not applied.

---

### ✅ Step 5: Look for Overriding Rules

CSS follows a priority system:

- Order in file
- Specificity
- Inline styles

Later rules can override earlier ones silently.

---

### ✅ Step 6: Validate Property & Value Pair

Check:

- Is the property valid?
- Is the value type correct?
- Does the browser support it?

Invalid values are ignored even if syntax is correct.

---

### ✅ Step 7: Strip CSS Down

If stuck:

- Comment out everything
- Add rules back one by one

This isolates the breaking point quickly.

---

## 🧰 Debugging Tools You Must Use

### 🔹 Browser DevTools

- Inspect elements
- View computed styles
- Toggle rules on/off

### 🔹 Commenting Technique

- Comment blocks of CSS
- Narrow down failure zones

### 🔹 Minimal Reproduction

- Reduce HTML to smallest possible case
- Reduce CSS to one rule

---

## ⚠️ Common Debugging Traps

Avoid these habits:

- Randomly changing values
- Adding `!important` blindly
- Copy-pasting without understanding
- Assuming layout is broken first

These slow learning and create bad habits.

---

## 🧠 Debugging Mindset Shift

Instead of asking:

> “Why isn’t this working?”

Ask:

> “What is the browser ignoring?”

This changes how you read CSS errors.

---

## 🧾 Summary

- CSS debugging is systematic, not random
- Syntax errors are the first suspects
- DevTools are mandatory, not optional
- Isolation beats guessing every time

> **Good CSS developers don’t guess — they inspect.**
