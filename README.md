# Seagrass Support Generator

**Website:** [Open the interactive Seagrass Lab demo](https://jane2632626881-a11y.github.io/seagrass-support-generator/)

The website follows the four Figma screens in order: define a placement area, set the environment and layout patterns, review the simulation workflow, then compare and export candidate schemes.

In step 2, layout patterns support multiple selection. Selecting **Gully guide curve** enables drawing on the map: click to add points and drag a point to adjust the curve. The guide needs at least two points before evaluation.

This is a front-end concept demo. The displayed shear-stress results are illustrative, and the STL download contains simple placeholder support blocks rather than the Grasshopper geometry. The original Grasshopper files remain in this repository.

GitHub Actions publishes the static website to GitHub Pages on pushes to `main` or `master`.

