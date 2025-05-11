# 🧱 Table Structuring in HTML

## 🎯 Purpose:

This section explains how to organize a table into separate sections for headers, body content, and footers using semantic HTML tags.

## 📑 Core Elements

| **Tag**      | **Description**         |
| ------------ | ----------------------- |
| `<thead>`    | Table header section    |
| `<tbody>`    | Table body section      |
| `<tfoot>`    | Table footer section    |

---

## 🔑 Summary:

- `<thead>`: Groups the **header rows** in a table.
  - Usually contains `<tr>` with `<th>` cells.
  - Helps browsers and screen readers **understand column headings**.
- `<tbody>`: Groups the **main content rows**.
  - Can contain one or more `<tr>` with `<td>` cells.
  - Multiple `<tbody>` sections are allowed but rarely used.
- `<tfoot>`: Groups the **footer rows**, often used for totals or summaries.
  - Can appear **before or after** `<tbody>` in code, but always renders at the bottom.
  - Often helps with **repeating footers** in printed tables.

---

⏭️ **Next:** Let’s Explore Forms and User Input Controls
