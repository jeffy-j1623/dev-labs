# 🎨 Inline Text Styles

## 🎯 Purpose:

This section explains inline formatting elements that modify text appearance without affecting document structure.

## 📑 Core Elements

| **Tag**    | **Description** |
| ---------- | --------------- |
| `<b>`      | Bold text       |
| `<strong>` | Important text  |
| `<i>`      | Italic text     |
| `<em>`     | Emphasized text |
| `<u>`      | Underlined text |
| `<sub>`    | Subscript       |
| `<sup>`    | Superscript     |
| `<del>`    | Deleted text    |
| `<ins>`    | Inserted text   |
| `<mark>`   | Highlights text |
| `<small>`  | Smaller text    |

---

## 🚀 My Learning Experience

- **Initial Challenge:**

  - I used `<b>` and `<i>` thinking they added emphasis or importance, but later understood they are purely **visual** and have **no semantic meaning**.
  - I also thought `<u>` was used for emphasis, but found it’s mainly for indicating **non-textual annotations** or **names in East Asian texts**, and overusing it may confuse users (as underlines often imply links).

- **Breakthrough Moment:**

  - When I started learning semantic HTML, I realized the difference between **presentational** and **semantic** tags. Tags like `<b>`, `<i>`, and `<u>` are now in my toolkit for styling **without meaning**.
  - I discovered that `<sub>` and `<sup>` are more than just visual tweaks — they have **actual semantic meaning** for math/science notation (e.g., H<sub>2</sub>O, E = mc<sup>2</sup>).

- **Noteworthy Discovery:**

  - `<small>` is not just for reducing font size — it's used for things like **disclaimers, copyright**, and **fine print**. That subtlety made my content more structured.
  - Learning how these tags render differently by default helped me clean up unnecessary CSS.

---

## 🔑 Summary:

- `<b>`, `<i>`, and `<u>` are **presentational**: use them when you want visual effects but not semantic meaning.
- `<sub>` and `<sup>` should be used when the **position of text has meaning**, such as chemical formulas or superscripted references.
- `<small>` is ideal for **fine print, legal notices, or additional notes**.
- Prefer semantic tags when meaning matters; use these when **visual representation** is the main goal.

---

⏭️ **Next:** Learn about Quotations and Citations.
