# Markdown Guidelines

Follow these rules when writing or editing Markdown files (e.g., README.md, AGENTS.md):

## General

- Use a single `#` top-level heading per file.
- Leave one blank line before and after headings, code blocks, lists, and tables.
- Use ATX-style headings (`#`, `##`, `###`). Do not use setext (underline) style.
- Do not skip heading levels (e.g., `##` → `####`).
- End the file with a single trailing newline.
- Limit line length to 120 characters where practical. Break long sentences across lines.

## Lists

- Use `-` for unordered lists.
- Use `1.` for ordered lists (Do not let the renderer auto-number, do it yourself).
- Indent nested lists by 4 spaces.

## Code

- Use fenced code blocks (triple backticks) with a language identifier.
- Use inline backticks for commands, file names, and short code references.

## Links and Images

- Prefer reference-style links (`[text][ref]`) when the same URL is used more than once.
- Add alt text to all images.

## Tables

- Align all columns so that pipes (`|`) line up vertically across every row, including the header and separator rows. Pad cells with spaces to equal width.
- Always include leading and trailing pipes on every row.

Good:

```markdown
| Tables   |      Are      |   Cool |
|----------|:-------------:|-------:|
| col 1 is | left-aligned  | $1600  |
| col 2 is | centered      |   $12  |
| col 3 is | right-aligned |    $1  |
```

Bad:

```markdown
| Tables | Are | Cool |
|---|:---:|---:|
| col 1 is | left-aligned | $1600 |
| col 2 is | centered | $12 |
| col 3 is | right-aligned | $1 |
```
