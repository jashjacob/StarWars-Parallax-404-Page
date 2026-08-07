Parallax 404 Page
========

404 Parallax Page featuring Yoda from StarWars built with parallax.js.

It's inspired from the GitHub 404 page with Star Wars. 

### 🌐 Live Demo
Visit the live demo on GitHub Pages: **[https://jashjacob.github.io/StarWars-Parallax-404-Page/](https://jashjacob.github.io/StarWars-Parallax-404-Page/)** 

## Performance & Asset Optimization

The original raw `.png` images had a total payload size of **3.78 MB**.

All image assets have been optimized using `pngquant` palette quantization and converted to next-gen `.webp` format via `cwebp`:

| Asset | Original PNG | Optimized PNG | Next-Gen WebP | Savings |
| :--- | :--- | :--- | :--- | :--- |
| `bg.png` | 811.0 KB | 286.7 KB | 101.2 KB | **-87.5%** |
| `bg-layer-1.png` | 1097.1 KB | 281.1 KB | 250.2 KB | **-77.2%** |
| `bg-layer-2.png` | 1508.2 KB | 404.0 KB | 389.1 KB | **-74.2%** |
| `yoda.png` | 410.8 KB | 107.5 KB | 54.8 KB | **-86.7%** |
| `yhr.png` | 22.9 KB | 4.6 KB | 13.3 KB | **-41.9%** |
| `404.png` | 16.5 KB | 3.4 KB | 8.3 KB | **-49.7%** |
| **Total** | **3.78 MB** | **1.06 MB** | **0.80 MB** | **~79% Total Reduction** |

Modern HTML `<picture>` elements are implemented in `404.html` to serve fast WebP images automatically with fallback to compressed PNGs.
