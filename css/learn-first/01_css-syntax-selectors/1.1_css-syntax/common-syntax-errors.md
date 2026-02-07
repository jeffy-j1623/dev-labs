# ⚠️ Common CSS Syntax Errors

## 🎯 Purpose

This document lists the **most common CSS syntax mistakes** beginners (and even experienced developers) make.

CSS does not throw visible errors for most syntax problems.  
Instead, it **silently ignores invalid rules or declarations**.

Knowing these mistakes helps you **debug faster** and **avoid frustration**.

---

## ❌ Error 1: Missing Semicolon

### What happens
- The browser may ignore the current declaration
- The next declaration may also break

### Why it happens
- Forgetting to end a line
- Assuming the last semicolon is optional

### Rule
> Always end **every declaration** with a semicolon.

---

## ❌ Error 2: Missing or Extra Braces `{ }`

### What happens
- Entire rule is ignored
- Following rules may also break

### Common causes
- Forgetting to close a rule
- Accidentally deleting a brace
- Copy-paste mistakes

### Rule
> Every `{` must have a matching `}`.

---

## ❌ Error 3: Missing Colon Between Property and Value

### What happens
- Declaration becomes invalid
- Browser ignores it completely

### Why it happens
- Typing fast
- Mixing HTML attribute syntax with CSS

### Rule
> Property and value **must** be separated by `:`.

---

## ❌ Error 4: Misspelled Property Names

### What happens
- Browser ignores the declaration
- No warning is shown

### Examples of common typos
- Wrong spelling
- Extra characters
- Incorrect property names

### Rule
> If a property doesn’t exist, CSS skips it silently.

---

## ❌ Error 5: Invalid Property Values

### What happens
- Property is ignored
- Other properties still work

### Why it happens
- Wrong unit
- Unsupported keyword
- Wrong value type

### Rule
> Property and value must **match expected types**.

---

## ❌ Error 6: Using HTML Syntax Inside CSS

### What happens
- CSS becomes invalid
- Browser ignores rules

### Common mistakes
- Writing HTML attributes inside CSS
- Using `=` instead of `:`

### Rule
> CSS syntax ≠ HTML syntax.

---

## ❌ Error 7: Incorrect Comment Syntax

### What happens
- Stylesheet breaks if comment is unclosed
- Rules below comment are ignored

### Common mistake
- Using `//` for comments

### Rule
> Only `/* comment */` works in CSS.

---

## ❌ Error 8: Forgetting Units Where Required

### What happens
- Declaration is ignored
- Property expects a unit

### Why it happens
- Assuming browser guesses unit
- Forgetting measurement type

### Rule
> Length values usually require units.

---

## ❌ Error 9: Case-Sensitive File Paths

### What happens
- CSS file doesn’t load
- Styles appear missing

### Why it happens
- Case mismatch in file names
- Different OS behavior

### Rule
> File paths are case-sensitive — always match exactly.

---

## ❌ Error 10: Writing CSS Outside a Rule Block

### What happens
- Browser ignores orphan declarations
- CSS appears not to work

### Why it happens
- Forgetting selector
- Removing braces accidentally

### Rule
> Declarations must always live inside a rule block.

---

## 🧠 Debugging Mindset

When CSS fails:

1. Don’t assume logic is wrong
2. Assume **syntax is broken**
3. Fix structure before tweaking values
4. Use DevTools to inspect ignored rules

> **CSS is not broken — your syntax is.**

---

## 🧾 Summary

- CSS syntax errors are silent but deadly
- One small mistake can invalidate rules
- Most issues are punctuation-related
- Learning error patterns speeds up debugging

> **Master syntax errors early to avoid pain later.**
