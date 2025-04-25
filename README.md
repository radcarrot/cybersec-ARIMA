# Cybersec-ARIMA

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Demo](#demo)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
- [Usage](#usage)  
  - [1. Simulate & Explore Data](#1-simulate--explore-data)  
  - [2. Train & Forecast ARIMA](#2-train--forecast-arima)  
  - [3. Detect & Visualize Anomalies](#3-detect--visualize-anomalies)  
- [Project Structure](#project-structure)  
- [Configuration](#configuration)  
- [Future Work](#future-work)  
- [Author](#author)  
- [License](#license)  

---

## Project Overview

This repository demonstrates how to use the **ARIMA** (AutoRegressive Integrated Moving Average) model for **anomaly detection** in time-series network traffic, targeting cybersecurity use cases. We:

1. **Simulate** synthetic “bytes per minute” traffic.  
2. **Inject** artificial spikes (anomalies).  
3. **Fit** an ARIMA model on normal data.  
4. **Forecast** expected traffic and compute residuals.  
5. **Flag** deviations as anomalies and visualize results.

---

## Features

- 📊 Synthetic traffic generation  
- 🔍 Stationarity testing (Augmented Dickey–Fuller)  
- 🤖 ARIMA modeling & optional auto-parameter tuning  
- 🚨 Residual-based anomaly detection (static & rolling thresholds)  
- 📈 Plots of time series, forecasts, residuals, and detected anomalies  
- 📝 Fully documented Jupyter Notebook  

---

## Demo

![Anomaly Demo](docs/anomaly_demo.png)  
*Example: red markers indicate detected anomalies.*

---

## Getting Started

### Prerequisites

- **Git**  
- **Python 3.7+**  
- [pip](https://pip.pypa.io/) or [conda](https://docs.conda.io/)  
- Jupyter Notebook or JupyterLab  

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/radcarrot/cybersec-ARIMA.git
   cd cybersec-ARIMA
