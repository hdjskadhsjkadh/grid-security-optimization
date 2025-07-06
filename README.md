Power Grid Security Optimization under High Renewable Penetration
🌍 Overview
This repository presents the research project "Optimization Strategies for Power Grid Security Carrying Capacity under High Renewable Energy Penetration", which proposes a deep learning-based adaptive optimization framework to ensure power grid security and resilience in the face of high variability from renewable energy sources like wind and solar.

🎯 Objectives
Improve the security carrying capacity of modern power grids.
Leverage advanced deep learning models to optimize grid stability and reduce curtailment.
Integrate real-time forecasting, dynamic reserve allocation, and probabilistic assessments for enhanced grid control.
🧠 Key Contributions
Curvature-Aware Adaptive Optimization (CAO):

Incorporates second-order curvature approximations.
Dynamically adjusts learning rates based on Hessian estimates.
Stabilizes optimization with momentum and damping strategies.
Adaptive Gradient-Based Optimization Strategy (AGOS):

Employs variance-reduced gradient estimation.
Features adaptive momentum regulation and curvature-aware learning rate scaling.
Achieves high convergence speed and robustness in complex optimization landscapes.
Hybrid Deep Learning Architecture:

Utilizes Graph Neural Networks (GNN) for grid topology modeling.
Employs LSTM for time-series forecasting of renewable sources.
Integrates Reinforcement Learning for real-time control policy adaptation.
Applies Explainable AI (XAI) techniques for interpretability and transparency.
📊 Experimental Setup
Datasets:

OEDI – U.S. energy data including consumption and meteorology.
OPSD – European power grid operation and market data.
Pecan Street – Residential-level smart meter data.
Solar Energy Prediction – Weather-informed solar power data.
Frameworks & Tools:

Developed using PyTorch.
Training on NVIDIA A100 GPU (40GB).
Sliding window forecasting with 48-step lookback and 24-step prediction horizon.
Evaluation Metrics:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Mean Absolute Percentage Error (MAPE)
R² Coefficient of Determination
📈 Results
Outperforms SOTA models like Transformer, LSTM, DeepAR, XGBoost, and TCN across all benchmark datasets.
Demonstrates superior resilience and accuracy in high-variability grid scenarios.
Ablation studies confirm the importance of CAO and AGOS components for optimal forecasting and scheduling.
🔍 Visualizations
Figures and diagrams (see pages 6–14 in the paper) illustrate:
Architecture of CAO and AGOS.
Comparison plots of model performance.
Heatmaps and boxplots from ablation studies.
