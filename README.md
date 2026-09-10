# Sorted Grid Search

A simple, beginner-friendly website for the DAA problem of finding a target value in a grid sorted both row-wise and column-wise.

## Features
- Enter an n × n grid
- Enter a target value
- Find the target coordinate
- Show the search path
- Highlight checked and found cells
- Validate sorted input
- No backend required

## Algorithm
Start at the top-right corner:
- Current = target → found
- Current > target → move left
- Current < target → move down

Time complexity: **O(n)**
Auxiliary space: **O(1)**

## GitHub Pages
Upload `index.html` and `README.md` to a GitHub repository, then enable GitHub Pages from **Settings → Pages → Deploy from branch → main → / (root)**.
