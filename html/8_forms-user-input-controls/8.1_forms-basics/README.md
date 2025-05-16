# 📝 Form Basics in HTML

## 🎯 Purpose:

This section explains how to create basic forms in HTML for collecting user input like text, numbers, emails, and more.

## 📑 Core Elements

| **Tag**     | **Description**       |
| ----------- | --------------------- |
| `<form>`    | Form container        |
| `<label>`   | Label for input       |
| `<input>`   | User input field      |

---

## 🔑 Summary:

- `<form>`: Wraps all form elements and defines **where to send data**.
  - **`action`**: URL where form data is sent.
  - **`method`**: HTTP method (`GET` or `POST`).

- `<label>`: Adds a **text label** for an input field.
  - **`for`**: Links the label to an `<input>` using its `id`.

- `<input>`: Used to create various **input fields** (text, email, number, etc.).
  - **`id`**: Gives the input a unique identifier (used by `<label>`).
  - **`type`**: Defines the input type (e.g., `text`, `email`, `password`).
  - **`name`**: Key used to **identify form data** when submitted.
  - **`value`**: Pre-fills the input with a **default value**.
  - **`placeholder`**: Adds hint text inside the input.
  - **`password`**: Hide the input text, ideal for entering passwords.

---

⏭️ **Next:** Let’s Explore Forms [Input-](https://github.com/jeffy-j1623/dev-labs/tree/main/html/8_forms-user-input-controls/8.2_forms-input-types).
