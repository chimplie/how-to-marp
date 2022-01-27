---
marp: true
theme: default
class: invert
paginate: true
header: 'How to Marp'
footer: 'Talent Agent by [Chimplie](https://chimplie.com)'

---
<!-- _paginate: false -->
<!-- _footer: '' -->
<!-- _header: '' -->

# How to Marp

Talent Agent by [Chimplie](https://chimplie.com)

---

# What is Marp?

An ecosystem for markdown-based presentations.

[https://marp.app/](https://marp.app/)

---
<!-- _class: lead -->

# Marp and Gitpod

Add a `.gitpod.yml`:

```yaml
vscode:
  extensions:
    - marp-team.marp-vscode  # To enable live edit in VS Code 
```

See [docs](https://www.gitpod.io/docs/config-gitpod-file).

---
<!-- _class: lead -->

# Your First Presentation

Create a Markdown file `MARP.md`:

```markdown
---
marp: true
theme: uncover
class: invert
paginate: true
header: 'Header Content'
footer: 'Footer Content'

---

# Header

Text
```

---

# Build-in Themes

Only `default`, `gaia` and `uncover` are provided at the moment. See [docs](https://github.com/marp-team/marp-core/tree/main/themes).
