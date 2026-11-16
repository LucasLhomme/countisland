# 🏝️ Count Island — Connected-Component Labeling in C

[![Language: C](https://img.shields.io/badge/Language-C-00599C.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Module: B-CPE-100](https://img.shields.io/badge/Epitech-B--CPE--100-blue.svg)](https://www.epitech.eu/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Academic Year: 2024-2025](https://img.shields.io/badge/Academic%20Year-2024--2025%20(Tek1)-blueviolet.svg)](#)

> **Count Island implements a recursive flood-fill algorithm in C** to identify, count, and label isolated landmasses on a 2D text map.

---

## 🧠 Algorithmic Mechanics

Traverses a 2D grid matrix:
- When an unlabeled land cell (`'X'`) is discovered, a recursive Depth-First Search (DFS) or Breadth-First Search (BFS) spreads across cardinal neighbors (North, South, East, West).
- All connected cells are overwritten with the island's numeric ID (`'0'`, `'1'`, `'2'`, ...).
- Returns the total count of isolated connected islands discovered.

---

## 📜 License

Licensed under the **MIT License with attribution** to Lucas Lhomme (Crabe).
