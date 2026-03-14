# AIMA Exercises — Website v3 (Material Design)

Material Design-inspired website for exercises from *Artificial Intelligence: A Modern Approach* by Stuart Russell and Peter Norvig.

## What It Does

Presents AIMA textbook exercises in a card-based Material Design interface. Features a table of contents landing page with chapter cards, and individual exercise pages with a fixed sidebar navigation. Currently includes two fully implemented exercise chapters (Introduction and Logical Agents) as a design demonstration.

## Architecture

Pure HTML/CSS static site with no build tools. Uses Bootstrap 4 for grid layout and custom CSS for the Material Design card aesthetic. Exercise pages feature a fixed sidebar nav and card-style exercise blocks with MathJax for LaTeX rendering.

## 🛠 Tech Stack

| | Technology | Purpose |
|---|---|---|
| 🎨 | HTML / CSS | Structure and Material Design styling |
| 📐 | Bootstrap 4 | Grid layout |
| 🔢 | MathJax 2.7 | LaTeX math rendering (exercise pages) |

## Getting Started

No build step required:

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Project Structure

```
├── index.html                  # Landing page / table of contents
├── intro_exercise_card.html    # Ch.1 Introduction exercises
├── knowledge_logic_card.html   # Ch.7 Logical Agents exercises
├── css/
│   ├── bootstrap*.css          # Bootstrap 4 framework
│   ├── cards.css               # Landing page card styles
│   └── cards-exercise.css      # Exercise page card styles
└── js/
    └── bootstrap*.js           # Bootstrap JS
```

## ⚠️ Known Issues

- Only 2 of 27 chapters have exercise pages implemented; remaining TOC links point to nonexistent files.
- Uses non-standard `<text>` HTML elements (works but not semantic).
- Search bar on landing page is non-functional (placeholder UI only).

## License

MIT — © Peter Norvig. Design by Kaustabh Ganguly.
