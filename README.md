🔍 Project Overview

-Baseline: Implemented, tested and modified the original ORION neural network.

-Optimization: Experimented with multiple optimizers (Adam,RMSprop) and loss functions to study their effect on convergence and accuracy.

-Architecture Modification: Introduced changes to the network structure to enhance feature extraction and classification on 3D data, namely highway blocks in 2 different fashions.

📂 Repository Structure
├── Datasets/                                                            # Datasets that have been used to train the network
├── Results/                                                             # Displayed the different train/test loss curves for each run
├── Data preparation/lmb-freiburg orion master data_preparation-Modelnet # MATLAB function to convert CAD files to voxels
├── 3D_Object_Recognition.ipynb                                          # Python Notbook with code and descriptions
├── 3D_Object_Recognition.py                                             # Py file with code
├── Progetto_deep_learning_Stefani_Minchella.pdf                         # Paper with detailed description of work and results
└── README.md                                                            # Project documentation

📊 Results

Baseline ORION performance established as reference.

Optimizer and loss function exploration highlighted trade-offs in speed vs. accuracy.

Modified architecture achieved improved recognition on test datasets with a tradeoff of a higher complexity.
