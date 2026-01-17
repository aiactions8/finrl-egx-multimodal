# Multimodal FinRL Trading System for the Egyptian Stock Market

## Overview
This repository contains the implementation of a multimodal reinforcement learning trading system based on the FinRL framework. The system is designed to study the feasibility of applying deep reinforcement learning techniques to the Egyptian Stock Exchange (EGX).

The project was developed as part of a Master's thesis and follows an end-to-end experimental pipeline, including data collection, preprocessing, multimodal data integration, model training, and out-of-sample evaluation.

---

## Traded Stocks
The experimental study focuses on the following EGX-listed stocks:
- Commercial International Bank (COMI)
- Alexandria Mineral Oils Company (AMOC)
- Elsewedy Electric (SWDY)

---

## Dataset Description
The dataset spans the period from January 2020 to December 2025 and includes:
- Historical daily stock prices
- Technical indicators
- Financial news sentiment
- Social media sentiment

The data is divided into:
- Training period: 2020–2023
- Testing period (out-of-sample): 2024–2025

This strict temporal split ensures the absence of look-ahead bias.

---

## Methodology
The experimental workflow is organized into the following stages:

1. Data collection for selected EGX stocks
2. Data preprocessing and technical indicator computation
3. News and social media sentiment analysis
4. Multimodal data fusion
5. FinRL trading environment construction
6. PPO agent training
7. Out-of-sample performance evaluation

Each stage is implemented in a dedicated Jupyter notebook.

---

## Project Structure
data/
├── raw/
│   └── prices_only.csv
│
├── processed/
│   └── multimodal_features.csv
│
├── sentiment/
│   └── sentiment_scores.csv
│
└── README.md



---

## Experimental Setup
- Algorithm: Proximal Policy Optimization (PPO)
- Initial Capital: 1,000,000 EGP
- Transaction Costs: Included
- Execution Platform: Google Colab

---

## Results
The experimental results are reported using standard financial performance metrics, including cumulative return, annualized return, Sharpe ratio, and maximum drawdown. The numerical results can be found in:


---

## Reproducibility
All experiments were conducted using Google Colab. To reproduce the results, execute the notebooks sequentially from `01` to `06`.

---

## Academic Disclaimer
This project is intended strictly for academic and research purposes and does not constitute financial advice.

Add README.md
