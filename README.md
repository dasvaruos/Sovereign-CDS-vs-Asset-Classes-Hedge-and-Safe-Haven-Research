# Sovereign-CDS-vs-Asset-Classes-Hedge-and-Safe-Haven-Research
Multiscale Financial Risk Analysis (MODWT)

A wavelet-based framework to analyze financial risk, volatility, and hedging dynamics across time horizons using Maximal Overlap Discrete Wavelet Transform (MODWT).

🚀 Why this matters

Traditional models treat time series uniformly. Markets don’t.

This project decomposes financial data into multiple time scales to uncover:

Hidden risk structures
Time-varying correlations
Scale-specific hedging opportunities
⚙️ What’s inside
MODWT Decomposition → preserves alignment, no downsampling
Wavelet Variance → volatility across horizons
Multiscale Beta (Hedge Ratios):
β
j
	​

=
Var(
w
~
i,j,t
	​

)
Cov(
w
~
CDS,j,t
	​

,
w
~
i,j,t
	​

)
	​

Hedging Effectiveness → evaluated per scale
📁 Structure
data/        → input time series  
notebooks/   → analysis & visualization  
src/         → MODWT + risk metrics  
results/     → outputs (variance, betas, plots)  
utils/       → preprocessing helpers  
📈 Key Insights
Risk is scale-dependent, not constant
Short-term = noise | Long-term = structure
Multiscale hedging → more efficient strategies
Safe-haven behavior varies across horizons
🛠️ Stack

Python • NumPy • Pandas • PyWavelets • Jupyter

🎯 Use Cases
Market & Credit Risk
ALM / Treasury Modeling
Quant Research & Portfolio Hedging
💡 Takeaway

A shift from time-domain thinking → frequency-domain intelligence for better financial decision-making.
