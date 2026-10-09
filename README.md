## Hi, I'm Nicolò

I build machine-learning and optimization tools for forecasting and quantitative finance

### Open source

15 pull requests merged into libraries used across ML and finance, most of them fixing silent numerical errors:

- **Apple MLX**: reductions over very large arrays (32-bit index overflow on CPU and GPU) ([#4549](https://github.com/ml-explore/mlx/pull/4549))
- **Amazon Chronos**: series lengths for categorical item ids in `predict_df` ([#537](https://github.com/amazon-science/chronos-forecasting/pull/537))
- **CVXPY** (5): MIP warm start for SCIP ([#3483](https://github.com/cvxpy/cvxpy/pull/3483)), `geo_mean` on any shape ([#3493](https://github.com/cvxpy/cvxpy/pull/3493)), tuple axes in `std`, axis behavior of `cvar`, axis checks for matrix norms
- **skfolio** (3): VaR, EVaR and sample-weight fixes in the risk measures
- **NautilusTrader** (2): wrong default moving averages in trading indicators
- Also **Qdrant**, **NumPyro** and **Qiskit Experiments**

In review: Microsoft FLAML (approved), the NVIDIA cuOpt interface in CVXPY, Unit8 Darts and Nixtla (conformal prediction intervals), QuantEcon.

### Research and projects

- **WorldQuant BRAIN**: #2 in Italy, Gold Level, 19 submitted alphas
- **Kaggle**: silver medal, 76th of 4,186 teams, AI Agent Security (OpenAI × Google × IEEE)
- **[MQFS](https://github.com/nicoloangileri/market-states-mqfs)**: open, reproducible quantitative-finance papers, e.g. [market regimes from correlation structure](https://github.com/nicoloangileri/market-states-mqfs), [electricity risk for AI data centres](https://github.com/nicoloangileri/mqfs-compute-energy), [constraint-preserving QAOA on IBM quantum hardware](https://github.com/nicoloangileri/quantum-portfolio-mqfs)
- **Qiskit Advocate** (IBM Quantum) and solver of Jane Street's monthly puzzles

Open to ML engineering and quant, swe, data, or anything similar, including remote and part-time contract work or project-contract.
[LinkedIn](https://www.linkedin.com/in/nicol%C3%B3angileri/)
