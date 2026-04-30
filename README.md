What this project is about<br>
This repo contains our work on 3D object recognition, built on top of the ORION neural network. We started by reproducing and testing the original architecture as a baseline, then explored how different optimizers (Adam, RMSprop) and loss functions affect training dynamics. From there, we modified the network itself by introducing highway blocks in two different configurations to see if we could squeeze out better performance on 3D data.

What's inside<br>
Datasets/ — the datasets used for training<br>
Results/ — loss curves for each run (train and test)<br>
Data preparation/ — a MATLAB script to convert CAD models into voxel grids (based on the lmb-freiburg orion pipeline)<br>
3D_Object_Recognition.ipynb — the main notebook, with code and inline explanations<br>
3D_Object_Recognition.py — standalone Python version of the same code<br>
Progetto_deep_learning_Stefani_Minchella.pdf — our write-up with full details on methodology and results<br>
README.md — you're reading it<br>

How it went<br>
The baseline gave us a solid reference point. Optimizer and loss function experiments revealed the usual speed-vs-accuracy tradeoffs. The modified architecture (with highway blocks) improved recognition accuracy on the test sets, though it comes with added model complexity.
