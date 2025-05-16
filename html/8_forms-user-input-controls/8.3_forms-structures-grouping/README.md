# 🧩 Forms Structure & Grouping in HTML

## 🎯 Purpose:

This section explains how to organize form fields semantically and visually using grouping elements like `<select>`, `<option>`, `<textarea>`, `<fieldset>`, and `<legend>`.

## 📑 Core Elements

  | **Tag**       | **Description**                                    |
  | ------------- | -------------------------------------------------- |
  | `<select>`    | Creates a dropdown menu.                          |
  | `<option>`    | Defines each item inside a `<select>`.            |
  | `<optgroup>`  | Groups related options in a dropdown.             |
  | `<textarea>`  | Multi-line input box.                              |
  | `<fieldset>`  | Groups related form fields together.              |
  | `<legend>`    | Caption for a `<fieldset>` group.                  |
  | `<input>`     | Collects various types of user input.              |


---

## 🔑 Summary:

  - `<select>`: Creates a **dropdown menu** for choosing one or more options.
      - **`name`**: Identifies the dropdown in form submission.

  - `<option>`: Represents an **individual item** in a dropdown list.
      - **`value`**: The **data sent** when this option is selected.
      - **`selected`**: Pre-selects this option by default.
      - **`disabled`**: Makes the option **unselectable**.

  - `<optgroup>`: Groups related `<option>` elements within a `<select>` for better organization.
      - **`label`**: Defines a label for the group, providing a visual separator in the dropdown.    

  - `<textarea>`: Allows **multi-line text input**.
      - **`name`**: Identifies the text area in submission.
      - **`rows`**: Sets the **visible height** (number of lines).
      - **`cols`**: Sets the **visible width** (number of characters).
      - **`placeholder`**: Adds hint text.

  - `<fieldset>`: Groups **related form elements** together.
      - Helps with **logical and visual grouping**.
      - Useful for **accessibility** and screen readers.

  - `<legend>`: Provides a **caption/title** for the `<fieldset>`.
      - Describes the **purpose** of the grouped fields.

  - `<input>`: A flexible tag used to collect various **types of user input**.
      - **`type`**: Defines the input type.
         - `checkbox`: Select multiple options.
         - `radio`: Select one from many.

---

⏭️ **Next:** 