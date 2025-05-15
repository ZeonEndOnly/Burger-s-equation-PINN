# Physics-Informed Neural Networks for Burgers' Equation  
**Solving Forward and Inverse Diffusion Problems in 1D**  

Implementation of Physics-Informed Neural Networks (PINNs) for solving both forward and inverse problems of diffusion modeled by Burgers' equation in one dimension.

## 📜 Overview
This repository contains:
- **Forward Problem**: Simulate diffusion dynamics using Burgers' equation:
- ∂u/∂t + u·∇u = ν∇²u

- **Inverse Problem**: Infer unknown diffusion coefficient λ from observed data
- Hybrid approach combining deep learning with physical constraints
- Residual-based adaptive weighting for improved convergence

## ✨ Features
- 🧠 **Dual Problem Solving**: Unified architecture for forward & inverse problems
- 🧮 **Physics-Constrained Learning**: Hard-coded Burger's equation residuals
- 📈 **Adaptive Weighting**: Dynamic loss balancing for stability
- 🖥️ **Visualization Tools**: Interactive plotting of solution evolution
- 📊 **Benchmarking**: Comparison against analytical solutions
- 🔬 **Reproducibility**: Seed control & configurable hyperparameters

## 🛠️ Installation
git clone https://github.com/yourusername/Burgers-PINN.git
cd Burgers-PINN
conda create -n pinn python=3.8
conda activate pinn
pip install -r requirements.txt # Includes PyTorch/TensorFlow, NumPy, Matplotlib





