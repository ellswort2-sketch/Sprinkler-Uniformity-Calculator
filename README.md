# Sprinkler Uniformity Calculator

An instructional, browser-based calculator for comparing square, rectangular,
and equilateral-triangle sprinkler arrangements using recovered Fresno State
SPACE catch-can profiles.

The calculator reports low-quarter distribution uniformity, Christiansen
uniformity, precipitation rate from the overlapped profile, precipitation rate
from sprinkler flow, a 5% dry-area scheduling coefficient, and sprinkler
density. It also provides an application-depth heatmap and CSV/JSON exports.

## GitHub Pages

This repository is a static site and needs no build process.

1. Upload `index.html` to the repository root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then click **Save**.

The site will appear at:

`https://ellswort2-sketch.github.io/Sprinkler-Uniformity-Calculator/`

## Profile model

Catch depths are stored at 2-foot radial increments. The calculator uses
piecewise-linear interpolation between readings and zero contribution beyond
the tested radius.
