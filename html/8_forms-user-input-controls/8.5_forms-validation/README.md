# ✅ Forms Validation in HTML

## 🎯 Purpose:

This section covers how to use built-in HTML validation attributes to ensure form fields meet certain rules before submission.

## 📑 Core Elements

| **Tag**    | **Description**                     |
| ---------- | ----------------------------------- |
| `<input>`  | Input field with validation support |

---

## 🔑 Summary:

- `<input>`: Used to collect user data and apply validation constraints.
  - **`required`**: Ensures the field must be filled out before submission.
  - **`min`**: Sets the minimum **numeric/date/time** value allowed.
  - **`max`**: Sets the maximum **numeric/date/time** value allowed.
  - **`step`**: Specifies legal intervals (e.g., step="0.01" for decimals).
  - **`minlength`**: Minimum number of characters required (for text inputs).
  - **`maxlength`**: Maximum number of characters allowed.
  - **`pattern`**: A **regular expression** pattern that the input must match.
  - **`title`**: Custom **tooltip message** shown on invalid input (used with `pattern`).
  - 🧠 Combine `pattern` with `title` to show friendly validation messages (e.g., `title="Only lowercase letters and numbers"`).


---

⏭️ **Next:** Lets Explore **CSS**
