# 🌧️ ERE Conditional Probability Dashboard

An interactive scientific web tool for analyzing the conditional probability structure of Extreme Rainfall Events (EREs) under different atmospheric regimes and temporal conditions.

---

## 🔬 Overview

This project visualizes:

- Conditional probability of extreme rainfall events:
  \[
  P(ERE \mid Regime, Month)
  \]

- Lagged regime influence on ERE occurrence:
  \[
  P(ERE_t \mid Regime_{t-\tau})
  \]

- Spatiotemporal conditioning across monsoonal regimes

---

## 📊 Key Features

### 1. Regime–Month Heatmap
Interactive visualization of:
- Monthly variability
- Regime-dependent extreme rainfall likelihood

### 2. Lagged Regime Matrix
Explores temporal memory effects:
- Lag 0–3 structure
- Decay of influence across time

### 3. Scientific Dashboard Interface
- Built using Plotly.js
- Fully browser-based (no backend required)

---

## 🧪 Methodology

The probability is computed as:

\[
P(ERE \mid R, M) = \frac{N_{ERE}(R, M)}{N_{All}(R, M)}
\]

Where:
- \(R\) = atmospheric regime
- \(M\) = month
- \(N_{ERE}\) = number of extreme rainfall events
- \(N_{All}\) = total occurrences

Lagged extension:

\[
P(ERE_t \mid R_{t-\tau}) = f(\tau)
\]

---

## 📁 Data

This repository currently uses **synthetic dummy data** for demonstration purposes.

Future versions will integrate:
- CHIRPS daily precipitation data
- Regime classification output
- Extreme rainfall thresholding (95th / 99th percentile)

---

## 🚀 Live Demo

👉 https://YOUR-NETLIFY-LINK.netlify.app

---

## 🛠️ Tech Stack

- HTML5 / CSS3 / JavaScript
- Plotly.js (visualization)
- Netlify (deployment)

---

## 📌 Scientific Contribution

This tool supports research on:

- Synoptic regime–rainfall relationships
- Extreme event precursors
- Lagged atmospheric conditioning
- Monsoon-driven variability in Southeast Asia

---

## 📄 Future Development

- Integration with CHIRPS gridded datasets
- Region-based analysis (R1S–R5SW)
- Real lagged regime extraction pipeline
- Exportable publication figures (PNG/PDF)

---

## ⚖️ License

MIT License (recommended for academic reproducibility)
