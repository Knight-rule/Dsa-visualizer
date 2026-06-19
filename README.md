<h1 align="center">📊 DSA Visualizer</h1>

<p align="center">
  <em>Interactive algorithm visualization tool for learning Data Structures & Algorithms</em>
</p>

<p align="center">
  <a href="https://knight-rule.github.io/dsa-visualizer"><img src="https://img.shields.io/badge/demo-live-brightgreen" alt="Live Demo"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## ✨ Features

- [x] **9 Sorting & Searching Algorithms** — Bubble, Selection, Insertion, Merge, Quick Sort, Binary Search, Linear Search, BFS, DFS
- [x] **Animated Bar Charts** — Watch algorithms execute step by step with smooth animations
- [x] **Speed Control** — Adjust animation speed from slow to lightning fast
- [x] **Step Counter** — Track every comparison and swap in real-time
- [x] **Dark Theme** — Easy on the eyes for late-night study sessions
- [x] **Graph Visualization** — Explore BFS and DFS on interactive graphs
- [x] **Zero Dependencies** — Pure vanilla JavaScript, no frameworks required

## 📸 Screenshot

![screenshot](screenshot.png)

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic markup and canvas elements |
| CSS3 | Animations, dark theme, responsive layout |
| JavaScript | Algorithm implementation and DOM manipulation |

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/knight-rule/dsa-visualizer.git

# Navigate to the project
cd dsa-visualizer

# Open in browser
open index.html
```

No build step or dependencies required — just open the HTML file!

## 📖 Usage

1. Select an algorithm from the navigation menu
2. Adjust the array size using the slider
3. Click **"Generate New Array"** to create random data
4. Click **"Sort"** or **"Search"** to start the visualization
5. Use the **speed slider** to control animation tempo
6. Watch the step counter increment as the algorithm runs

## ⚙️ How It Works

```
┌─────────────┐    ┌──────────────┐    ┌─────────────┐
│  User Input  │───▶│  Algorithm   │───▶│  Animated   │
│  (Controls)  │    │  Engine      │    │  Renderer   │
└─────────────┘    └──────────────┘    └─────────────┘
                          │
                   ┌──────▼──────┐
                   │   Step Log   │
                   └─────────────┘
```

The visualizer uses a step-recording approach:
1. **Algorithm Execution** — Each algorithm records every comparison, swap, and shift
2. **Step Queue** — Operations are queued with metadata (indices, values, types)
3. **Animation Loop** — Steps are dequeued and rendered with configurable delays
4. **Color Coding** — Bars are colored to highlight comparisons, swaps, and sorted elements

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prashant** — [@knight-rule](https://github.com/knight-rule)

<p align="center">
  Made with ❤️ for students learning algorithms
</p>
