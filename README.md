# Community Garden Crop Yield Optimization

**[View the Live Project Report](https://amranbuilds.github.io/R-Project-Community-Garden-Crop-Yield-Optimization/)**

### Project Overview
This project utilizes linear programming to determine the optimal spatial allocation for three crops (tomatoes, carrots, and beans) in a 3,000 square foot community garden. The objective is to maximize total nutritional yield (kilocalories) while strictly adhering to physical resource limits and nutritional demand targets designed to supplement a 30-person community.

### Methodology
* **Algorithm:** Simplex Algorithm
* **Language:** R
* **Libraries:** `lpSolve`
* **Constraints Modeled:** Physical area, water availability, labor capacity, proportional crop diversity, and minimum protein production thresholds.

### Repository Contents
* `optimizing-veggetable-harvest.Rmd`: The source R Markdown script containing the mathematical formulation and executable R code.
* `index.html`: The rendered HTML output document hosted via GitHub Pages.
