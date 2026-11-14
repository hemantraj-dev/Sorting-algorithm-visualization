# SortLab — Sorting Algorithm Visualizer

A responsive, browser-based sorting algorithm visualizer. It runs entirely on the client and can be hosted for free with **GitHub Pages**.

## Features

- 13 sorting algorithms: Bubble, Selection, Insertion, Merge, Quick, Heap, Shell, Counting, Radix, Cocktail Shaker, Comb, Gnome, and Bucket Sort.
- Animated array bars with comparison, movement, pivot, and sorted-state colors.
- Random, nearly sorted, reverse sorted, few-unique, and custom arrays.
- Array-size and animation-speed controls.
- Start, pause, step-forward, and reset controls.
- Live comparison and write/swap counters.
- Complexity overview and pseudocode panel.
- Responsive layout for desktop, tablet, and mobile.
- No build tools, frameworks, or dependencies required.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

You can also use VS Code's Live Server extension.

## Deploy on GitHub Pages

1. Create a **public** GitHub repository, for example `sorting-visualizer`.
2. Upload `index.html` and `README.md` to the repository's root folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait a minute or two. GitHub will show your published website URL on the Pages settings screen.

Your URL will look like:

`https://YOUR-USERNAME.github.io/sorting-visualizer/`

Replace `YOUR-USERNAME` with your GitHub username. If your repository has a different name, the URL path will use that repository name.

## Update the website

After changing files, commit and push them to the `main` branch. GitHub Pages will publish the updated static site.

## Project structure

```text
sorting-visualizer/
├── index.html
└── README.md
```

## Notes

- This is a static website. It does not require Node.js, React, a server, or a database.
- GitHub Pages is suitable for this frontend-only project.
- The performance counters describe operations performed by the visualizer. Displayed elapsed time includes animation and browser scheduling, so it is intended for learning rather than rigorous algorithm benchmarking.
- Counting Sort and Radix Sort are intended for integer arrays.
- For best results, keep the array size moderate when using the slower quadratic-time algorithms.

## License

You may use, modify, and share this project for learning and educational purposes.
