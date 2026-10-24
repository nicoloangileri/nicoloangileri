## Hi, I'm Nicolò

I build machine-learning and optimization tools for forecasting and quantitative finance

### Open source

32 pull requests merged into libraries used across ML, quantum computing and finance

- **OpenAI Tart**: container-registry authentication with spaces between `WWW-Authenticate` directives, as RFC 7235 allows ([#1377](https://github.com/openai/tart/pull/1377))
- **NVIDIA cuOpt** (2): nightly CI for its CVXPY integration on images without a C++ compiler ([#2101](https://github.com/NVIDIA/cuopt/pull/2101)), and a minimize default for the objective sense of its MPS data model ([#2181](https://github.com/NVIDIA/cuopt/pull/2181))
- **Apple MLX**: reductions over very large arrays (32-bit index overflow on CPU and GPU) ([#4549](https://github.com/ml-explore/mlx/pull/4549))
- **Amazon Chronos**: series lengths for categorical item ids in `predict_df` ([#537](https://github.com/amazon-science/chronos-forecasting/pull/537))
- **QuantLib** (2): underflow in the non-central chi-square distribution ([#2908](https://github.com/lballabio/QuantLib/pull/2908)), and a faster Heston variance mesher for small vol of vol ([#2940](https://github.com/lballabio/QuantLib/pull/2940))
- **CVXPY** (6; top external contributor by commits in the 90 days to October 22, 2026, and 34th of 239 contributors all time): silent wrong answers on mixed-integer problems with NVIDIA cuOpt ([#3555](https://github.com/cvxpy/cvxpy/pull/3555)), MIP warm start for SCIP ([#3483](https://github.com/cvxpy/cvxpy/pull/3483)), `geo_mean` on any shape ([#3493](https://github.com/cvxpy/cvxpy/pull/3493)), tuple axes in `std`, axis behavior of `cvar`, axis checks for matrix norms
- **skfolio** (6): VaR, EVaR and sample-weight fixes in the risk measures, drawdown contributions, the Bodnar-Okhrin shrinkage of expected returns, and sample weights in the empirical covariance ([#417](https://github.com/skfolio/skfolio/pull/417))
- **NautilusTrader** (2): wrong default moving averages in trading indicators
- **QuantEcon**: ARMA impulse responses and simulations that came out delayed when p > q ([#976](https://github.com/QuantEcon/QuantEcon.py/pull/976))
- **Nixtla StatsForecast**: finite-sample conformal prediction intervals, shared with the Conformal Seasonal Pool model ([#1246](https://github.com/Nixtla/statsforecast/pull/1246))
- **Unit8 Darts** (2): conformal prediction intervals ([#3227](https://github.com/unit8co/darts/pull/3227)) and compatibility with pandas 3.1 ([#3289](https://github.com/unit8co/darts/pull/3289))
- **FinRL** (AI4Finance): tradability check on the price instead of the first indicator in `StockTradingEnv` ([#1456](https://github.com/AI4Finance-Foundation/FinRL/pull/1456))
- **Pasqal Pulser**: lazy conjugate/negative tensors converted to NumPy without resolving them ([#1130](https://github.com/pasqal-io/Pulser/pull/1130))
- **gcsopt** (graphs of convex sets): compatibility with the new CVXPY solving chain ([#23](https://github.com/TobiaMarcucci/gcsopt/pull/23))
- Also **Qdrant**, **NumPyro** (2) and **Qiskit Experiments**

In review: NVIDIA cuOpt (MPS writer), Microsoft FLAML, AutoGluon, Nixtla StatsForecast, Open GenAI Stack (formerly Llama Stack), MLX-VLM, SciPy.

### Research and projects

- **Research assistant** to Prof. Semyon Malamud (Swiss Finance Institute, EPFL), replicating and extending large factor pricing models
- **WorldQuant BRAIN**: #2 in Italy, Gold Level, 19 submitted alphas
- **Kaggle**: silver medal, 76th of 4,186 teams, AI Agent Security (OpenAI × Google × IEEE)
- **[MQFS](https://github.com/nicoloangileri/market-states-mqfs)**: open, reproducible quantitative-finance papers, e.g. [market regimes from correlation structure](https://github.com/nicoloangileri/market-states-mqfs), [electricity risk for AI data centres](https://github.com/nicoloangileri/mqfs-compute-energy), [constraint-preserving QAOA on IBM quantum hardware](https://github.com/nicoloangileri/quantum-portfolio-mqfs)
- **Qiskit Advocate** (IBM Quantum) and solver of Jane Street's monthly puzzles

Open to ML engineering, quant, software and data roles, including remote, part-time or project-based contracts, and to research projects.
[LinkedIn](https://www.linkedin.com/in/nicol%C3%B3angileri/)
