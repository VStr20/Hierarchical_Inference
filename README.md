# Hierarchical Inference Framework

This repository implements a hierarchical inference framework designed for resource-constrained edge devices (EDs) and edge servers (ESs). The system uses a small-size ML model (S-ML) on the ED and a large-size ML model (L-ML) on the ES to optimize inference accuracy while managing resource constraints.

## Overview

The key idea is to leverage an online meta-learning framework to:
1. Predict the correctness of the S-ML inference on the ED.
2. Decide whether to offload data to the ES for a more accurate inference using the L-ML model.

This approach minimizes computational overhead on the ED while ensuring robust performance.

## Features

- **Hierarchical Inference**: Combines local predictions with offloading mechanisms for enhanced accuracy.
- **Meta-Learning**: Adapts predictions dynamically based on model performance and input data characteristics.
- **Resource Optimization**: Balances computation and communication costs between the ED and the ES.


## Installation

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/VStr20/Hierarchical_Inference.git
   cd Hierarchical_Inference
