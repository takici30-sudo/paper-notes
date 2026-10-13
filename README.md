# Paper Notes

A browser notebook with a two-panel editor, basic Markdown preview, local saving, and `.md` export. Built with HTML, CSS, and JavaScript. No dependencies or build step.

## 使用方法 / Getting started

Open `index.html` in a modern browser. Write in the left panel; the right panel updates as you type. Click **Download .md** to export the current note.

直接双击 `index.html` 即可写笔记，左侧编辑、右侧预览，支持下载 Markdown 文件。

## Supported Markdown

- Headings: `#`, `##`, and `###`.
- Unordered and ordered lists.
- Blockquotes beginning with `>`.
- Fenced code blocks and horizontal rules.
- Plain paragraphs, with line breaks preserved.

This intentionally small renderer does not support inline formatting, links, images, tables, or nested lists. HTML is displayed as text rather than executed. The word count uses whitespace-separated words; Chinese text is better represented by the character count.

## Saving

One note is saved to this browser's `localStorage`. There is no server, account, sync, or backup. Clearing browser data can remove the note. Local-file persistence depends on the browser; use a static host such as GitHub Pages for consistent origin-based storage. Export important notes with the Download button.

## Customize

Change the CSS variables for the theme and the `sample` string for the starting note. Everything is contained in `index.html`.

This is a starter template; no automated tests or dependency installation were performed.
