# 📝 Quotations & Citations

## 📌 Purpose

This section explores the HTML semantic tags used to mark up quotations, citations, and related concepts like abbreviations and definitions. Understanding these tags is essential for creating accessible, well-structured content, particularly in academic, literary, and informative writing.

---

## 📌 Core Elements

| **Tag**        | **Type**    | **Description**                                     |
| -------------- | ----------- | --------------------------------------------------- |
| `<blockquote>` | Block-level | Defines long block quotations from another source   |
| `<q>`          | Inline      | Inline short quotations (auto adds quotation marks) |
| `<cite>`       | Inline      | Title of a creative work or cited source            |

---

## 🚀 My Learning Experience

- **Initial Challenge:**

  - At first, I struggled with understanding the difference between `<q>` and `<blockquote>`. Both are used for quotations, but I wasn’t sure when to use one over the other. I also misunderstood the purpose of the `<cite>` tag, thinking it was only used for linking to URLs rather than referencing the title of a creative work.
  - I figured it out by testing things out on my [Blog](https://github.com/jeffy-j1623/dev-portfolio/blob/main/mini-projects/psycology-blog.html) , using `<q>` for short quotes within sentences, `<blockquote>` for longer ones, and `<cite>` to give proper credit to the source. It clicked when I saw it in action.
  - I practiced using these tags in various scenarios, like writing blog posts and adding quotes from books or articles. I found that combining `<cite>` with `<blockquote>` helped me give proper credit to the original source of longer quotes.

- **Breakthrough Moment:**

  - The breakthrough came when I realized the significance of using these tags for accessibility. The browser adding quotation marks around `<q>` made my code cleaner and easier to maintain. I also recognized that using `<cite>` for titles rather than just URLs made my content more structured and meaningful, improving the overall readability and usability.

- **Noteworthy Discovery:**

  - I discovered that using `<blockquote>` for longer quotations ensures that the attribution is clear, and the optional `cite` attribute allows me to link back to the original source.
  - I also learned that using `<cite>` for referencing titles of works helps with both search engine optimization (SEO) and accessibility. It’s not just a visual cue, but a semantic one that makes the content more meaningful.
  - I applied this knowledge in a personal blog project, where I used `<blockquote>` for large excerpts from books, and `<q>` for smaller, inline quotes. This practice not only helped structure my content but also enhanced its clarity and reliability.

---

## 📌 Summary

- **`<blockquote>`** is used for longer, block-level quotations, often with an optional `cite` attribute to link back to the source.
- **`<q>`** is for inline quotes, and browsers automatically add quotation marks.
- **`<cite>`** is used to reference the title of creative works (books, articles, movies, etc.).

---

🚀 **Next:** Move to [Text-Semantics](https://github.com/jeffy-j1623/dev-labs/tree/main/html/2_text-formating/2.4_text-semantics) to explore semantic elements in HTML.