# Sorting Visualized

Interactive visualizations of sorting algorithms — in the spirit of [DeFi Visualized](https://expectfun.github.io/defi-visualized/), but for algorithms.

## Algorithms

- **Bubble Sort** — compare neighbors, O(n²)
- **Insertion Sort** — insert into sorted portion
- **Selection Sort** — select minimum each step
- **Quick Sort** — pivot and partition, O(n log n) on average
- **Merge Sort** — split and merge, stable O(n log n)
- **Heap Sort** — heap, O(n log n) in-place

## Run locally

Open `index.html` in a browser or start a local server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then open http://localhost:8000 (or the port from the command output).

## Structure

- `index.html` — home page with algorithm cards
- `styles.css` — shared styles (dark theme, cards, viz panel)
- `bubble-sort.html`, `insertion-sort.html`, … — pages with visualization, Play/Shuffle buttons, speed and size sliders

Inspired by [DeFi Visualized](https://expectfun.github.io/defi-visualized/).
