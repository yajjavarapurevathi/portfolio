# Revathi Yajjavarapu Portfolio

This version intentionally contains only the three projects represented in Revathi's GitHub portfolio:

1. Enterprise Demand Forecasting Platform
2. Insurance Customer Segmentation & Churn Prediction
3. NLP Metaphor Detection using DistilBERT

## Update the existing GitHub Pages site

From inside this folder:

```bash
git init
git add .
git commit -m "Keep only three portfolio projects"
git branch -M main
git remote add origin https://github.com/yajjavarapurevathi/portfolio.git
git push -u origin main --force
```

A safer alternative is to copy these updated files over the existing local `revathi_portfolio_full` repository and then run:

```bash
git add .
git commit -m "Update portfolio to three projects"
git push
```

The safer alternative preserves the existing repository history.
