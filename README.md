my_neural_network_project/
│
├── data/                      # Data management (Excluded from Git)
│   ├── raw/                   # Original, immutable data (ReadOnly)
│   ├── processed/             # Cleaned, preprocessed, or augmented data
│   └── external/              # Data from external sources (e.g., pre-trained weights)
│
├── models/                    # Model checkpoints and final artifacts
│   ├── checkpoints/           # Intermediate model weights saved during training (Epochs)
│   └── final/                 # Final, production-ready models
│
├── notebooks/                 # Jupyter Notebooks for initial research and EDA
│   ├── 1.0_data_exploration.ipynb
│   └── 2.0_initial_training.ipynb
│
├── src/                       # Source code of the project (Stand-alone Python package)
│   ├── __init__.py
│   ├── data_loader.py         # Data loading, Dataset, and DataLoader creation
│   ├── models.py              # Neural network architecture definitions
│   ├── train.py               # Training loop, loss functions, and optimizers
│   ├── evaluate.py            # Evaluation metrics and test set inference
│   └── utils.py               # Helper functions (logging, saving files, visualization)
│
├── tests/                     # Unit tests for your code
│   └── test_models.py
│
├── config.yaml                # Configuration file (Hyperparameters: LR, Batch Size, etc.)
├── .gitignore                 # Ignores heavy files and directories (data/, checkpoints/)
├── README.md                  # Project documentation and setup instructions
└── requirements.txt           # Python dependencies (PyTorch, TensorFlow, etc.)
