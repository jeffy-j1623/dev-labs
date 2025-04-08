# 📝 Quotations & Citations

## 🎯 Purpose:

This section covers semantic tags that represent quotations, citations, definitions, and abbreviations. These tags add structure, meaning, and context to your content, especially in academic or informative writing.

---

## 📑 Core Elements

| **Tag**        | **Type**    | **Description**                                                       |
| -------------- | ----------- | --------------------------------------------------------------------- |
| `<blockquote>` | Block-level | Defines long block quotations from another source                     |
| `<q>`          | Inline      | Inline short quotations (auto adds quotation marks)                   |
| `<cite>`       | Inline      | Title of a creative work or cited source                              |
| `<abbr>`       | Inline      | Abbreviations/acronyms, with optional tooltip using `title` attribute |
| `<dfn>`        | Inline      | Defines a term being introduced for the first time                    |

---

## 🔍 Attribute Use

| **Tag**        | **Important Attribute** | **Purpose**                        |
| -------------- | ----------------------- | ---------------------------------- |
| `<abbr>`       | `title`                 | Shows full form on hover           |
| `<blockquote>` | `cite`                  | (Optional) URL of the quote source |
| `<q>`          | `cite`                  | (Optional) Citation URL            |

---

## 🚀 My Learning Experience

- Initial Challenge:

  - I didn’t know the difference between `<q>` and `<blockquote>`, and I didn’t realize `<cite>` was for titles, not just URLs.

- Breakthrough:

  - Learned to use `<abbr title="...">` for accessibility — now readers and screen readers both get value!

  - Found that `<dfn>` helps in glossaries and documentation.

- Cool Use Case:

  - I used `<cite>` to style book titles and `<blockquote>` in blog posts with attribution links.

  ***

  ## 🔑 Summary:

  - Use `<blockquote>` for long quotes with optional citation links.

  - Use `<q>` for inline quotes — browser automatically adds quotation marks.

  - Use `<cite>` for works (books, reports, articles, songs).

  - Use `<abbr>` for acronyms with title to show expanded form.

  - Use `<dfn>` when defining a new term in documentation or learning resources.

---

⏭️ **Next:** Learn about Text Semantics
