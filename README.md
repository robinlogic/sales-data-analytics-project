# 📊 Convenience Store Analytics – Ongoing Business Study Overview

This repository contains a series of applied data analysis projects conducted on real point-of-sale data from a family-run convenience store operating since March 2025.

The goal of this project series is to support evidence-based business decisions around:

* Inventory management

* Capital efficiency

* Product portfolio design

* Cross-selling and basket behaviour

* Pricing and traffic-driving strategies

Each study focuses on a specific operational problem faced by the store, using transaction-level data to generate actionable insights.

### 📁 Project Structure
```
/cigarettes-cross-sales-study
    ├── study_in_cigarettes.ipynb
    ├── data/
    └── README.md

... < more_coming_soon >
```

## 📌 Current Study: Cigarettes as Traffic Drivers & Capital Lock-Up Business problem

Cigarettes account for a large share of revenue but operate on extremely thin margins and require high upfront capital. Customers also perceived cigarette prices as uncompetitive.

This raised a strategic question:

**Should cigarette inventory be reduced to free capital, or do cigarettes play a deeper role in driving profitable store traffic?**

## Key questions explored

* How significant are cigarettes in revenue vs volume?

* Do cigarette purchases generate cross-sales?

* Which cigarette storekeeping units (SKUs) contribute meaningful indirect value?

* How should cigarette products be structured from a portfolio perspective?

## Methods

* Transaction aggregation (monthly and SKU-level)

* Cross-sale basket construction

* Conditional basket metrics

* Average cross-sale revenue per cigarette

* Average cross-sale item depth per cigarette

* Product-level cross-ratio analysis

* Portfolio quadrant framework (demand × basket role)

* Time-series behavioural analysis around price changes

## Core findings

* Cigarettes contribute ~20% of revenue but <5% of volume, locking up large amounts of capital.

* ~33% of cigarette packs are sold with other items, particularly beverages and convenience goods.

* After price reductions, cigarette volume rose sharply. Although basket quality initially deteriorated, cross-sales steadily recovered.

* Cigarettes function as traffic anchors, not standalone profit drivers.

* Cross-sale impact is uneven across SKUs. A small subset of products reliably support baskets, while many contribute little indirect value.

## Business implications

* Cigarettes should not be evaluated purely on margins.

* Competitive cigarette pricing can be viable when paired with cross-category optimisation.

* High-impact cigarette SKUs should be prioritised for availability.

* Cross-sale companion categories (especially beverages and alcohol) should be co-managed.

* Inventory strategy should shift from “how many cartons” to “what roles do products play.”

## Limitations

* No product-level cost or profit data

* No stockout or lost-sales visibility

* Observational (non-causal) transaction data

* Some SKU patterns driven by concentrated customer behaviour

* No formal demand forecasting or inventory optimisation yet

## Next steps

Planned future studies include:

* Stockout detection and lost-sales estimation

* SKU-level demand forecasting

* Beverage and snack margin optimisation

* Basket-based product placement analysis

* Capital allocation modelling

# 🧠 Why this project exists

This project serves both as:

a real decision-support system for a small retail business, and

an applied analytics portfolio demonstrating end-to-end problem solving, from messy POS data to business strategy.
