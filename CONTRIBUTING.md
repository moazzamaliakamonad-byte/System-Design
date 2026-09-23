# 🤝 Contributing to System Design Notes

First off — thank you for even considering contributing. This project exists to make system design genuinely fun and accessible, and contributions that push that forward are always welcome.

---

## 🧭 Before You Start

Please read this entire file before opening a PR. It will save both of us time.

---

## 🗣️ Reporting Issues

If you find:
- A **factual error** in an explanation
- A **broken interaction** or visual glitch
- A **concept that's missing** or under-explained
- A **typo or grammar issue**

→ Open a [GitHub Issue](../../issues) and describe the problem clearly. Include the filename and what you expected vs what you saw.

---

## ✅ What Kind of Contributions Are Welcome

| Type | Welcome? |
|---|---|
| Fix a factual error | ✅ Yes |
| Add a missing concept | ✅ Yes |
| Improve an explanation | ✅ Yes |
| Add a new interactive simulation | ✅ Yes (discuss first via issue) |
| Add a new topic page | ✅ Yes (discuss first via issue) |
| Improve accessibility / mobile layout | ✅ Yes |
| Add external JS frameworks / libraries | ❌ No — keep it vanilla |
| Change the visual design significantly | ❌ Discuss first |
| Auto-generated / AI-dumped content | ❌ Hard no |

---

## 🛠️ How to Contribute (Step by Step)

### 1. Fork & Clone

```bash
git clone https://github.com/<your-username>/System-Design.git
```

### 2. Create a Branch

Name it clearly:

```bash
git checkout -b fix/cap-theorem-typo
git checkout -b feature/add-redis-page
git checkout -b improve/load-balancer-animation
```

### 3. Make Your Changes

Follow the **code style guide** below before committing.

### 4. Test Locally

Open your HTML file(s) in a browser and verify:
- All interactions work
- Quiz answers are correct
- Animations don't break on resize
- It looks good on mobile too (resize the window)
- No console errors

### 5. Commit With a Clear Message

```bash
git commit -m "fix: correct CAP theorem consistency explanation"
git commit -m "feat: add Redis eviction policy simulation"
git commit -m "improve: smoother animation on load balancer diagram"
```

### 6. Open a Pull Request

- Describe **what** you changed and **why**
- Link to the relevant issue if one exists
- Add a screenshot or screen recording if it is a visual change

---

## 🎨 Code Style Guide

### HTML
- One self-contained `.html` file per concept
- No external CDN dependencies — everything inlined or bundled
- Use semantic HTML (`<article>`, `<section>`, `<aside>`, etc.)
- All pages must have a `<title>` and meta description

### CSS
- Styles go in a `<style>` block in `<head>`
- Use CSS custom properties (`--color-primary`, etc.) for theming
- Mobile-first media queries

### JavaScript
- Vanilla JS only — no React, Vue, jQuery, etc.
- All scripts go in a `<script>` block before `</body>`
- No `console.log` left in production code
- Comment any non-obvious logic

### Content
- Write like you are explaining to a friend, not writing a Wikipedia article
- Every concept needs a **real-world analogy** (the "what this is like in real life")
- Every page needs at least one **interactive element**
- Memes and humor are encouraged — keep them **text-based** (no external images)
- Do NOT just dump AI-generated text. Write, edit, make it yours.

---

## 🔍 Page Template

When adding a **new topic page**, follow the existing structure:

1. **Header** — Topic name, one-line description, difficulty badge
2. **The Analogy** — Real-world comparison before any technical content
3. **Core Concept** — The actual explanation with diagrams/animations
4. **Deep Dive** — Accordion sections for advanced details
5. **Code Example** — Syntax-highlighted snippet
6. **Real World** — How Netflix / Amazon / Google actually use this
7. **Quiz** — 3–5 questions
8. **Meme** — Because rules

---

## 💬 Questions?

Open an issue with the `question` label. Happy to discuss anything!

---

<div align="center">
  <sub>Built on the principle that if learning is boring, the content failed — not the learner.</sub>
</div>
