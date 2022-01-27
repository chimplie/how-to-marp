---
marp: true
theme: default
paginate: true
header: '![](./images/logo.svg) Let it Marp'
footer: '[Talent Agent](https://agent.chimplie.com/) by [Chimplie](https://chimplie.com)'

---
<!-- _paginate: false -->
<!-- _footer: '' -->
<!-- _header: '' -->
<!-- _class: invert -->

# How to Marp ![](./images/logo.svg)

[Talent Agent](https://agent.chimplie.com/) by [Chimplie](https://chimplie.com)

---
<!-- _class: invert -->

# What is Marp?

An ecosystem for markdown-based presentations.

[https://marp.app/](https://marp.app/)

---

# Marp and Gitpod

Add a `.gitpod.yml`:

```yaml
vscode:
  extensions:
    - marp-team.marp-vscode  # To enable live edit in VS Code 
```

See [docs](https://www.gitpod.io/docs/config-gitpod-file).

---

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
<!-- _class: invert -->

# Marp Syntax

Check the [docs](https://marpit.marp.app/markdown).

---
<!-- _class: invert -->

# Build-in Themes

Only `default`, `gaia` and `uncover` are provided at the moment. See [docs](https://github.com/marp-team/marp-core/tree/main/themes).

---
<!-- _class: invert -->
<!-- _paginate: false -->
<!-- _footer: '' -->
<!-- _header: '' -->

# Happy Marping! ![](./images/logo.svg)

[Talent Agent](https://agent.chimplie.com/) by [Chimplie](https://chimplie.com)
