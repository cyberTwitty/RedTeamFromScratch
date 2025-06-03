# Git Commit Message Cheatsheet

> This guide captures best practices for clear, purposeful, and consistent commit messages.

---

## 🔖 Types

| Type        | Use When... |
|-------------|-------------|
| `feat`      | You’re adding new content (notes, payloads, tools, diagrams) |
| `fix`       | You’re correcting something broken (typos, formatting, wrong links) |
| `docs`      | You’re editing Markdown-only content (README, notes, cheatsheets) |
| `refactor`  | You’re reorganizing code or content without changing its meaning |
| `chore`     | You’re doing repo upkeep (file cleanup, folder rename, badge updates) |
| `style`     | You’re updating only visual elements (spacing, headings, icons, etc.) |
| `test`      | You’re adding or fixing lab walkthroughs or test cases |

---

## 📌 Writing Good Summaries

### ✅ Good

- `feat: add XSS real-world breach summary`
- `fix: update broken OWASP SSRF link`
- `docs: clarify SSRF reflection language`
- `refactor: streamline folder structure for Day01`

### ❌ Avoid

- `update stuff`
- `misc changes`
- `typo lol`

---

## 💡 Extras

### Multiple Types (optional)

`feat(docs): add SSRF notes and cleanup old references`

### Longer Commit? Use Body

```markdown
feat: add notes for SSRF file upload edge cases

This includes examples for bypassing validation using image polyglots,
and potential IDOR chaining if uploads return file paths.
```
