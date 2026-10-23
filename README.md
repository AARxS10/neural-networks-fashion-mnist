# CSC2042S Assignment 3: Neural Networks (RHMABD006)

## Files
- `CSC2042S_Assignment3_NeuralNetworks_2026.ipynb`: notebook with data loading, baseline MLP, 27-run hyperparameter experiment, results tables, plots and written answers.
- `report.pdf`: report (max 5 pages) on design decisions, results and discussion.
- `README.md`: this file.

## Setup
1. Python 3.10+ with the packages: `pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn`
2. Open the notebook in Jupyter and choose Run All (run the cells top to bottom).
3. On the first run, Fashion-MNIST is downloaded automatically by torchvision into `./data` (internet needed once). No data is included in this submission.

## Notes
- The random seed is fixed (42) so results are reproducible.
- The full experiment (27 runs x 10 epochs) takes about 40 minutes on CPU, much less on a GPU.
