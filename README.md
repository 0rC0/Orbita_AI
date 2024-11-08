# Orbita AI

code for the paper (citation pending):
```
Deep Learning Model for Automated Segmentation of Orbital Structures in MRI Images
```

### Directory contents
- `scripts/`: exemplificatory sbatch script for Slurm cluster
- `notebooks/`: contains the code for training and testing the model on a local machine

### Notebooks
- `MakeUNetDataset.ipynb`: creates the five-fold cross-validation datasets for nnU-Net
- `grab_train_results.ipynb`: grabs the training results from the nnU-Net training logs
- `grab_test_results.ipynb`: calculate DSC for the test sets
- `Volumes.ipynb`: calculate the volumes of the orbital structures

