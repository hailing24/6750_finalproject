# Spatial Bias in PM2.5 Monitoring Networks in Los Angeles County

**DSAN 6750 – GIS for Spatial Data Science**
**Author:** Hailing Liao

---

## Overview

This repository contains the full workflow for my final project in DSAN 6750.
The goal is to examine whether PM2.5 monitoring stations in Los Angeles County are spatially biased toward major road corridors, and whether the network shows clustering beyond complete spatial randomness.

All results, maps, and statistical outputs are summarized in the project website generated from `index.qmd`. The rendered HTML (`_site/index.html`) serves as the final project report.

---

## How to Reproduce the Website

1. Install R packages:

```r
install.packages(c(
  "sf", "spatstat.geom", "spatstat.core",
  "spatstat.random", "ggplot2", "dplyr", "terra"
))
```

2. Open **index.qmd** in RStudio or VS Code.

3. Render the website:

```bash
quarto render index.qmd
```

4. The final site will appear in:

```
_site/index.html
```

This file is the complete project summary.

---

