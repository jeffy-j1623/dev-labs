# 📏 CSS Units

## 🎯 Purpose:

CSS units define **how lengths, sizes, and spacing** are measured in stylesheets. They are essential for creating flexible, responsive, and well-proportioned layouts across different screen sizes and devices.

---

## 📐 CSS Unit Types & Usage

### 📦 Absolute Units

| **Unit** | **Name**              | **Description**                                  |
|----------|-----------------------|--------------------------------------------------|
| `px`     | Pixels                | Fixed size unit; most commonly used              |
| `pt`     | Points                | 1/72 of an inch; used mostly in print styles     |
| `pc`     | Picas                 | 1 pica = 12 points                               |
| `in`     | Inches                | 1 inch = 96 pixels                               |
| `cm`     | Centimeters           | Metric unit                                      |
| `mm`     | Millimeters           | Metric unit                                      |

---

### 🔁 Relative Units

| **Unit** | **Name**                   | **Description**                                                |
|----------|----------------------------|----------------------------------------------------------------|
| `%`      | Percent                    | Relative to parent element                                     |
| `em`     | Em                         | Relative to the **parent's** font size                         |
| `rem`    | Root Em                    | Relative to the **root (`<html>`)** font size                  |
| `ch`     | Character Width            | Width of the "0" character in the current font                 |
| `ex`     | x-Height                   | Height of the lowercase "x" of the font                        |
| `lh`     | Line Height                | Relative to the computed line-height of the element            |
| `rlh`    | Root Line Height           | Relative to the root element’s line-height                     |

---

### 🌐 Viewport Units

| **Unit** | **Name**             | **Description**                                   |
|----------|----------------------|---------------------------------------------------|
| `vw`     | Viewport Width       | 1% of the width of the viewport                   |
| `vh`     | Viewport Height      | 1% of the height of the viewport                  |
| `vmin`   | Viewport Min         | Smaller of `vw` and `vh`                          |
| `vmax`   | Viewport Max         | Larger of `vw` and `vh`                           |
| `vi`     | Viewport Inline      | 1% of the inline (horizontal) viewport size       |
| `vb`     | Viewport Block       | 1% of the block (vertical) viewport size          |
| `svw`    | Small Viewport Width | Safe area of small screen `vw` (iOS Safari, etc.) |
| `svh`    | Small Viewport Height| Safe area of small screen `vh`                    |
| `lvw`    | Large Viewport Width | Based on maximum `vw` size                        |
| `lvh`    | Large Viewport Height| Based on maximum `vh` size                        |
| `dvw`    | Dynamic Viewport Width| Dynamically adjusts with viewport                |
| `dvh`    | Dynamic Viewport Height| Dynamically adjusts with viewport               |

---

### ✒️ Typography-Relative Units (New & Niche)

| **Unit** | **Name**                  | **Description**                                        |
|----------|---------------------------|--------------------------------------------------------|
| `cap`    | Capital Height            | Height of uppercase letters in current font            |
| `ic`     | Ideographic Character     | Width of a CJK character (Chinese, Japanese, Korean)   |
| `rlc`    | Root Line Cap Height      | Relative to cap height of root line box (rare)         |

---

### 🧮 Layout Units (CSS Grid & Flexbox)

| **Unit** | **Name**       | **Description**                                |
|----------|----------------|------------------------------------------------|
| `fr`     | Fraction Unit  | Used in CSS Grid to divide space proportionally|

---

## 📚 Resources

- [CSS Units Reference – MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)
- [W3Schools: CSS Units](https://www.w3schools.com/cssref/css_units.asp)
- [CSS Tricks: A Complete Guide to CSS Units](https://css-tricks.com/the-lengths-of-css/)

---

## 🔑 Summary

- **Absolute units**: have fixed size — ideal for print or strict layouts.
- **Relative units**: scale based on parent or root values — great for responsive design.
- **Viewport units**: adapt to screen size — excellent for fluid layouts.
- **Font-relative units**: adjust with font metrics — ideal for typography control.
- **Grid unit `fr`** is used to distribute space proportionally in **CSS Grid**.
- Use **responsive units** for flexible, modern layouts.

---

⏭️ **Next:** Lets study about CSS Properties and its Values.