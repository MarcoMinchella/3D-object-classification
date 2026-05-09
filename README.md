# 3D Object Recognition

## What this project is about

This repo contains our work on 3D object recognition, built on top of the **ORION** neural network. We started by reproducing and testing the original architecture as a baseline, then explored how different optimizers (Adam, RMSprop) and loss functions affect training dynamics. From there, we modified the network itself by introducing **highway blocks** in two different configurations to see if we could squeeze out better performance on 3D data.

-----

## What’s inside

```
.
├── Data preparation/                              # MATLAB script to convert CAD models into voxel grids
│                                                  # (based on the lmb-freiburg ORION pipeline)
├── Datasets/                                      # The datasets used for training
├── Results/                                       # Loss curves for each run (train and test)
├── 3D_Object_Recognition.ipynb                    # Main notebook, with code and inline explanations
├── 3D_Object_Recognition.py                       # Standalone Python version of the same code
├── Progetto_deep_learning_Stefani_Minchella.pdf   # Full write-up with methodology and results
└── README.md                                      # You're reading it
```

-----

## How it went

The baseline gave us a solid reference point. Optimizer and loss function experiments revealed the usual speed-vs-accuracy tradeoffs. The modified architecture (with highway blocks) improved recognition accuracy on the test sets, though it comes with added model complexity.

Full details, plots, and discussion are in `Progetto_deep_learning_Stefani_Minchella.pdf`.