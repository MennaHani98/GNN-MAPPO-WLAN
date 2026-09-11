# GNN-MAPPO for Wi-Fi Resource Allocation

## Overview

This repository contains the implementation of the proposed **GNN-MAPPO framework** for resource allocation in Wireless Local Area Network (WLAN) environments.

The framework combines:

- **Graph Neural Networks (GNNs)** to model relationships and interactions among network entities.
- **Multi-Agent Proximal Policy Optimization (MAPPO)** for multi-agent decision-making.
- A simulated Wi-Fi/WLAN environment for training and evaluating the proposed framework.

The repository is provided to support the reproducibility of the experimental results reported in the associated manuscript.

---

## Repository Structure

```text
GNN-MAPPO-WLAN/
│
├── wifi_rfl.ipynb
├── README.md
├── requirements.txt
│
└── wifi_logs/
    ├── episodes_20260826_18355...
    ├── evaluation_20260826_18355...
    ├── training_20260826_18355...
    ├── wifi_rl_best_model.pth
    └── wifi_rl_checkpoint.pth

## Files
wifi_rfl.ipynb
The main implementation file containing the WLAN simulation environment, the proposed GNN-MAPPO framework, training procedures, and evaluation experiments.

wifi_rl_best_model.pth
A pre-trained model checkpoint that can be used for evaluation without repeating the complete training process.

requirements.txt
Contains the Python dependencies required to run the implementation.

## Running the Code: Google Colab

The implementation can be executed using Google Colab.
Upload or open wifi_rfl.ipynb in Google Colab.
Install the required dependencies.
Ensure that the model checkpoint wifi_rl_best_model.pth is available in the expected directory.
Run the notebook cells in sequence.

## Training

The notebook includes the training procedure for the proposed GNN-MAPPO framework.
The training configuration and simulation parameters are defined within the notebook.
To reproduce the training process, execute the training cells in the provided notebook.

## Evaluation

The repository includes evaluation procedures for assessing the performance of the trained GNN-MAPPO model.
A pre-trained checkpoint is provided:
wifi_rl_best_model.pth
The checkpoint can be used to evaluate the trained policy without repeating the full training process.

## Reproducibility

To support reproducibility, this repository provides:
WLAN simulation environment
GNN-MAPPO implementation
Training procedure
Evaluation procedure
Experimental configuration
Pre-trained model checkpoint
Dependency information

For reproducible experiments, the random seeds and experimental settings used in the implementation should be retained as provided in the notebook.

## Citation

If you use this implementation in your research, please cite the associated paper.

Citation information will be added upon publication.

## License

This repository is intended for research and academic use.