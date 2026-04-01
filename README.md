# The AI Reference Library

An open-source collection of practitioner guides covering artificial intelligence — from foundational concepts to advanced systems. Built for students, business professionals, and curious minds. No engineering background required.

**Live site → [sathishkumaralagiri.github.io/ai](https://sathishkumaralagiri.github.io/ai/)**

---

## What this is

A structured, self-contained learning journey through AI — organised by level and designed to be read in order or dipped into by topic. Every module is a standalone HTML page: no frameworks, no build steps, no dependencies beyond a web browser.

---

## Structure

The library is organised as a learning journey across four levels.

### 🟢 Beginner

| # | Category | Modules |
|---|---|---|
| 1 | 🧱 Foundations | What is AI? · History & concepts · Key terminology · What AI can't do |

### 🟡 Intermediate

| # | Category | Modules |
|---|---|---|
| 2 | 🔢 Data & Statistics | What is Data? · Types of data · Basic statistics · Data to insight |
| 3 | 🤖 Machine Learning | What is ML? · Supervised learning · Training & testing · Common algorithms · Model evaluation |
| 4 | 📊 Data Science | What do data scientists do? · The data pipeline · DS vs ML vs AI · Tools of the trade |

### 🔴 Advanced

| # | Category | Modules |
|---|---|---|
| 5 | ✨ Generative AI | How LLMs work · Text generation · Image & audio generation · Multimodal AI |
| 6 | 🕹️ Agentic AI | From generation to action · What are AI agents? · Planning, memory & tools · Multi-agent systems · Risks & limitations |

### 🔵 Applied

| # | Category | Modules |
|---|---|---|
| 7 | 🛠️ Working with AI | Prompt engineering · Using ChatGPT / Claude / Gemini · AI tools by use case |
| 8 | 🏢 AI in Business | Use cases by industry · Building an AI strategy · ROI & measuring impact |
| 9 | ⚖️ Ethics & Society | Bias & fairness · Privacy & data · Jobs & future of work · Regulation |

**Total: 9 categories · 36 modules · all live**

---

## File structure

```
index.html
foundations/
  style.css                          ← shared stylesheet for every page
  index.html
  what-is-ai/index.html
  history/index.html
  terminology/index.html
  what-ai-cant-do/index.html
data-statistics/
  index.html
  what-is-data/index.html
  types-of-data/index.html
  basic-statistics/index.html
  data-to-insight/index.html
machine-learning/
  index.html
  what-is-ml/index.html
  supervised-learning/index.html
  training-testing/index.html
  common-algorithms/index.html
  model-evaluation/index.html
data-science/
  index.html
  what-data-scientists-do/index.html
  data-pipeline/index.html
  ds-vs-ml-vs-ai/index.html
  tools-of-the-trade/index.html
generative-ai/
  index.html
  how-llms-work/index.html
  text-generation/index.html
  image-audio-generation/index.html
  multimodal-ai/index.html
agentic-ai/
  index.html
  gen-to-agentic/index.html
  what-are-agents/index.html
  planning-memory-tools/index.html
  multi-agent-systems/index.html
  risks-limitations/index.html
working-with-ai/
  index.html
  prompt-engineering/index.html
  using-ai-tools/index.html
  ai-tools-by-use-case/index.html
ai-in-business/
  index.html
  use-cases-by-industry/index.html
  building-ai-strategy/index.html
  roi-measuring-impact/index.html
ethics-society/
  index.html
  bias-fairness/index.html
  privacy-data/index.html
  jobs-future-of-work/index.html
  regulation/index.html
```

---

## Tech stack

Pure HTML and CSS — no frameworks, no build tools, no JavaScript dependencies.

- **Fonts** — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) + [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) + [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro) via Google Fonts
- **Stylesheet** — one shared file: `foundations/style.css` — used by every page in the library
- **Hosting** — GitHub Pages, deployed directly from the `main` branch root

---

## Contributing

Contributions are welcome — corrections, improved explanations, new modules, or translations.

1. Fork the repository
2. Create a branch: `git checkout -b fix-module-name` or `git checkout -b add-module-name`
3. Follow the structure below for new module pages
4. Submit a pull request with a clear description

### Module page structure

Every module page should include the following elements in order:

```html
<!-- 1. Nav bar (consistent across all pages) -->
<!-- 2. Breadcrumb trail back to home -->
<!-- 3. Article header with:
        - module-tag (showing category and level)
        - article-title with <em> for italic accent
        - article-meta with read time and module number -->
<!-- 4. Article body with:
        - introductory paragraph
        - h2 section headings
        - at least one .callout or .example-box
        - summary-box with key takeaways at the end -->
<!-- 5. article-nav with prev/next links -->
<!-- 6. Footer -->
```

Every module page links to `../../foundations/style.css` (or `../foundations/style.css` for category index pages).

### Writing style

- Plain English — assume intelligent readers with no technical background
- Avoid jargon without explanation
- Use concrete examples and analogies rather than abstract definitions
- Be honest about limitations and uncertainty — don't oversell AI
- Intermediate and advanced modules may include light Python or SQL examples

---

## Deployment

This site deploys automatically to GitHub Pages on every push to `main`.

To set up GitHub Pages: **Settings → Pages → Source: Deploy from branch → Branch: main / (root)**

---

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

You are free to share and adapt this material for any purpose, including commercially, as long as you give appropriate credit.

---

Built by [sathishkumaralagiri](https://github.com/sathishkumaralagiri) · Tambaram, Chennai · 2026
