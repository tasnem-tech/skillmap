# SkillMap 🧠

**AI-powered interactive learning path visualizer** — type any skill, get a beautiful knowledge graph.

![SkillMap Demo](https://img.shields.io/badge/demo-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Vanilla JS](https://img.shields.io/badge/stack-HTML%20%2B%20D3.js-orange)

## What it does

SkillMap uses Claude AI to generate a structured knowledge graph for any skill you enter. It maps:

- **Root node** — the core skill you want to learn
- **Sub-domains** — major areas or prerequisites
- **Concepts/techniques** — specific tools, algorithms, and ideas

Each node is interactive: click it to see a description and curated learning resources.

## Features

- 🤖 Powered by Claude claude-sonnet-4-20250514 (Anthropic API)
- 🔗 Force-directed graph built with D3.js
- 🖱️ Drag, zoom, and pan the graph
- 📖 Click any node for description + resources
- 💾 Export the graph as JSON
- 🌑 Dark theme, zero dependencies beyond D3 + Google Fonts
- 🗂️ Single HTML file — no build step, no framework

## Quick Start

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/skillmap.git
   cd skillmap
   ```

2. Open `index.html` in your browser (or serve it locally):
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```

3. Enter your [Anthropic API key](https://console.anthropic.com/) in the sidebar

4. Type any skill and hit **Generate Map →**

## Example Skills to Try

- `machine learning`
- `system design`
- `rust programming`
- `kubernetes`
- `computer vision`
- `data engineering`

## Tech Stack

| Tool | Purpose |
|------|---------|
| [D3.js v7](https://d3js.org/) | Force-directed graph layout |
| [Claude API](https://anthropic.com) | Skill graph generation (structured JSON) |
| [DM Sans / DM Serif Display](https://fonts.google.com/) | Typography |
| Vanilla JS + HTML/CSS | Everything else |

## How it Works

1. You enter a skill + your API key
2. A carefully crafted prompt asks Claude to return a structured JSON graph
3. D3.js renders the graph with physics-based layout
4. Clicking nodes fetches descriptions and resource links from the AI response

## API Key

Your API key is stored **only in memory** (never in localStorage, never sent anywhere except `api.anthropic.com`). It's cleared when you refresh the page.

You can get an API key at [console.anthropic.com](https://console.anthropic.com/).

## Customization

The graph prompt is in the `fetchSkillGraph()` function in `index.html`. You can modify it to:
- Change the depth or breadth of the graph
- Add difficulty ratings to nodes
- Include estimated learning hours
- Request different resource types

## License

MIT — use it however you like.

---

Built with Claude AI + D3.js · [Open an issue](../../issues) if you find bugs
