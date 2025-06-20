# 📏 CSS Dimensions

## 📌 Purpose
CSS dimensions define the physical size and space of HTML elements. They play a fundamental role in designing layouts, spacing, and responsiveness across devices. They can override default dimensions or set dimensions where none exists.

---

## 📌 Core Elements

| Property          | Description |
|------------------|-------------|
| `width`          | Sets the width of the content area. |
| `height`         | Sets the height of the content area. |

### 🧮 CSS Units

#### 📐 Absolute Units
| Unit | Description                |
|------|----------------------------|
| `px` | Pixels – fixed unit.       |
| `cm` | Centimeters                |
| `mm` | Millimeters                |
| `in` | Inches                     |
| `pt` | Points (1/72 of an inch)   |
| `pc` | Picas (1 pica = 12 points) |

#### 📏 Relative Units
| Unit   | Description |
|--------|-------------|
| `%`    | Percentage relative to parent element. |
| `em`   | Relative to the font-size of the element. |
| `rem`  | Relative to the root element's font-size. |
| `vw`   | Relative to 1% of the viewport width. |
| `vh`   | Relative to 1% of the viewport height. |
| `vmin` | 1% of the smaller of vw or vh. |
| `vmax` | 1% of the larger of vw or vh. |

---

## 🔑 Summary

- Use relative units (%, vw, vh, em, rem) for responsive design.
- Use absolute units (px, cm, in) for fixed-size elements.
- By default, width and height control only the content area.
- Be careful with `height` — let content define it when possible.
- Make images/media responsive using `height: auto`.

---

⏭️ **Next:** Lets Explore about CSS Box Model.