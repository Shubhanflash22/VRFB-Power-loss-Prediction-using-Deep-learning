# Optimization of Renewable Energy Storage ⚡🔋

A machine learning and deep learning project focused on improving the efficiency and cost-effectiveness of renewable energy storage systems by predicting power loss under varying conditions.

## Table of Contents

* [Project Overview](#project-overview)
* [Dataset](#dataset)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Models](#models)
* [Results](#results)
* [Future Work](#future-work)
* [License](#license)

## Project Overview

This project aims to optimize renewable energy storage systems by predicting power losses based on states of charge and electrolyte flow rates. Using machine learning and deep learning models, the project enhances prediction accuracy to improve energy storage efficiency and reduce costs.

Key steps include:

* Modeling multiple predictive frameworks using ANN, LSTM, and RNN.
* Predicting power loss under varying operational conditions.
* Comparing model performance to existing approaches to maximize prediction accuracy.

## Dataset

* Dataset contains measurements of power loss, states of charge, and electrolyte flow rates for energy storage systems.
* Includes historical system performance data under different operating conditions.
* Preprocessed and normalized to facilitate model training.

## Features

* **Power Loss Prediction:** Predict energy loss at various states of charge and electrolyte flow rates.
* **Model Comparison:** Evaluate ANN, LSTM, and RNN for predictive accuracy.
* **Optimization:** Use predictions to optimize energy storage system efficiency and cost.

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/VRFB-Power-loss-Prediction-using-Deep-learning.git
cd renewable-energy-storage

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Pip install dependencies

```

## Usage

1. Prepare your dataset in the required CSV format.
2. Complete Code for ANN is :

```bash
ANN.py
```

2. Complete Code for LSTM is :

```bash
LSTM.py
```

4. Data and best models are in the zips:

```bash
ANN.zip
LSTM.zip
```

## Models

* **ANN (Artificial Neural Network):** Fully connected network for baseline prediction.
* **LSTM (Long Short-Term Memory):** Captures temporal dependencies in energy storage data.
* **RNN (Recurrent Neural Network):** Models sequential patterns in system behavior.
* All models aim to predict power loss more accurately than existing approaches.

## Results

* Each model improved prediction accuracy of existing models by 40–70%.
* Provides actionable insights for energy storage optimization and cost reduction.

## Future Work

* Incorporate more real-time operational data from diverse energy storage systems.
* Explore hybrid models combining ANN and LSTM for further performance improvements.
* Deploy models in real-time energy management systems for renewable energy grids.

## Citation

If you use this work, please cite:

```bibtex
@software{VRFB-Power-loss-Prediction-using-Deep-learning,
  author = {Shubhan Mital},
  title = {VRFB Power loss Prediction using Deep learning},
  year = {2025},
  url = https://github.com/Shubhanflash22/VRFB-Power-loss-Prediction-using-Deep-learning.git
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
