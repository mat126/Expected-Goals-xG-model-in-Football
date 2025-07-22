# 📊 Plots Directory

This directory contains all plots generated during the Expected Goals (xG) modeling and evaluation process. The contents are organized into subfolders for clarity and reproducibility.

---

## 📁 `validation_metrics/`

Contains evaluation plots for each predictive model, grouped by dataset:

- `OpenPlay_Foot/`
- `SetPiece_Foot/`
- `OpenPlay_Head/`
- `SetPiece_Head/`

Each of these contains:
- ROC curves
- Confusion matrices (threshold 0.3)
- Calibration curves

---

## 📁 `interactive_viz/`

Contains interactive and descriptive plots that help visualize spatial patterns, distributions, and insights from the raw data.

Examples:
- Interactive shot maps (e.g. Messi’s shots)
- Corner heatmaps

These are mainly stored as `.html` files for interactivity (e.g., Plotly, Folium, etc.).

---

## 🔖 Notes

- All PNG and HTML files are named using the pattern: `metric_model_dataset.ext`
- Interactivity requires opening the HTML files in a browser

---