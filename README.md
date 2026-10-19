
<!--
GitHub Profile README
Before publishing:
1. Verify the repository URLs below.
2. Add your LinkedIn and professional email if you want them public.
3. Confirm the displayed degree, tools, and project metrics.
-->

<div align="center">

# Julius-Scissor

### Applied Mathematics · Quantitative Finance · Statistical Learning

**Building and evaluating quantitative models through mathematics, statistics, and code.**

[![Focus](https://img.shields.io/badge/FOCUS-QUANT%20RESEARCH-064E3B?style=flat-square)](https://github.com/Julius-Scissor)
[![Domain](https://img.shields.io/badge/DOMAIN-APPLIED%20MATHEMATICS-065F46?style=flat-square)](https://github.com/Julius-Scissor)
[![Status](https://img.shields.io/badge/STATUS-OPEN%20TO%20RESEARCH-064E3B?style=flat-square)](https://github.com/Julius-Scissor)

</div>

---

## About

I'm an **Integrated BS–MS student in Applied Mathematics at IISER Thiruvananthapuram**, interested in quantitative finance, statistical modelling, machine learning, and mathematical optimisation.

My work focuses on turning mathematical ideas into reproducible computational experiments. I enjoy building end-to-end pipelines, comparing models against sensible baselines, and examining whether apparent performance holds up under out-of-sample evaluation.

**Current research interests**
- Quantitative research and financial time series
- Factor investing and portfolio optimisation
- Statistical learning and predictive modelling
- Numerical methods and mathematical modelling
- Machine learning applications in motorsport strategy

I'm particularly interested in projects where mathematical reasoning, careful validation, and implementation matter as much as the final metric.

---

## Featured Projects

### 01 · Factor Investing & Portfolio Optimisation

**Python · NumPy · pandas · SciPy · scikit-learn · yfinance**

An experimental quantitative-investing pipeline exploring factor-based portfolio construction in Indian equities.

- Investigates momentum and low-volatility signals across a five-equity universe.
- Implements long-only minimum-variance and maximum-Sharpe portfolio optimisation.
- Examines portfolio weights, covariance estimates, and sensitivity to modelling choices.
- Evaluates portfolio behaviour against equal-weight and NIFTY 50 benchmarks, with out-of-sample and walk-forward analysis.

**Research question:** How sensitive are portfolio allocations and observed performance to factor definitions, estimation choices, and evaluation methodology?

[**Explore the repository →**](https://github.com/Julius-Scissor/factor-investing-portfolio-optimization)

---

### 02 · Neural Network-Based Market Direction Classification

**Python · PyTorch · scikit-learn**

A financial machine-learning project investigating whether historical NIFTY 50 data can help classify market direction.

- Compares logistic regression, feed-forward neural networks, and LSTM models.
- Uses chronological validation and held-out testing rather than relying only on random splits.
- Applies train-only scaling and forward-label boundary purging to reduce data leakage.
- Extends predictive evaluation to open-to-open backtesting with explicit transaction-cost assumptions.

**Key finding:** The experiments did not establish a reliable out-of-sample trading edge. The project documents the evaluation methodology and limitations rather than treating classification performance alone as evidence of profitability.

[**Explore the repository →**](https://github.com/Julius-Scissor/Financial-Market-Direction-ML)

---

### 03 · F1 TyreMind

**Python · pandas · NumPy · scikit-learn · OpenF1**

*Ongoing project*

A machine-learning and race-strategy project exploring tyre degradation and stint-level performance in Formula 1.

- Builds a data pipeline from historical session and lap data.
- Uses the 2024 Bahrain Grand Prix FP2 session as an initial case study.
- Examines tyre degradation across drivers and stints as a foundation for modelling stint performance.
- Aims to extend the model towards race-stint planning, tyre allocation constraints, and session-specific information from practice and qualifying.

**Preliminary experiment:** A linear-regression baseline reported MAE of approximately **1.756 seconds** and RMSE of **2.178 seconds** on a random split of the initial dataset. These are preliminary results, not evidence of generalisation to unseen races; more rigorous temporal and race-level validation is needed.

**Next steps:** Improve feature engineering, evaluate degradation-aware models, and develop strategy simulations under circuit-specific constraints.

[**Explore the repository →**](https://github.com/Julius-Scissor)

---

## Technical Toolkit

| Area | Tools and methods |
|---|---|
| **Programming** | Python |
| **Data analysis** | NumPy, pandas |
| **Machine learning** | scikit-learn, PyTorch |
| **Optimisation & scientific computing** | SciPy, numerical methods |
| **Quantitative methods** | Regression, portfolio optimisation, factor analysis, financial time-series modelling |
| **Mathematical foundations** | Linear algebra, probability, mathematical statistics, numerical analysis |
| **Research workflow** | Jupyter notebooks, LaTeX, Git, GitHub |

*Tools listed here should reflect what I have personally used in the corresponding projects.*

---

## Research Approach

I aim to build projects around a few principles:

- **Mathematical clarity:** understand the assumptions behind a model, not just its implementation.
- **Sound evaluation:** use appropriate baselines, chronological splits, and out-of-sample testing where relevant.
- **Reproducibility:** document data processing, modelling choices, and experimental limitations.
- **Honest conclusions:** distinguish a useful predictive signal from a robust, implementable strategy.
- **Iterative improvement:** start with interpretable baselines before adding model complexity.

---

## Currently Exploring

- More robust factor-investing and portfolio-evaluation methods
- Financial time-series validation and leakage-resistant backtesting
- Statistical and machine-learning approaches to tyre degradation
- The relationship between predictive accuracy, risk, and practical decision-making

---

## Contact

I'm interested in **research internships, quantitative research, and collaborative projects** in applied mathematics, statistics, financial modelling, and machine learning.

- **GitHub:** [Julius-Scissor](https://github.com/Julius-Scissor)
- **LinkedIn:** [Armaan Singh](www.linkedin.com/in/armaan-singh-536357210)
- **Email:** [armaan24@iisertvm.ac.in](armaan24@iisertvm.ac.in)

<div align="center">

*Mathematical foundations. Reproducible experiments. Evidence over assumptions.*

</div>
