# DiffDock-DSMBind

An SE(3) denoising score-matching model for unsupervised binding energy prediction built on the DiffDock codebase. The model learns to predict the energy $E_\theta(X)$, calculates the gradient $\nabla_X E_\theta(X)$ with respect to the input coordinates (representing atom forces), and uses this gradient to infer translation and rotation noise. The learned energy $E(X)$ is hypothesized to correlate with experimental binding energy.
