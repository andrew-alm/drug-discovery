# Collection of Drug Discovery Demos
The repo is used to track some of the different DL drug discovery papers I have explored. 

### Demos
#### [EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction](https://arxiv.org/abs/2202.05146): 
Given a ligand, or a set of ligands, this model uses SE(3)-equivariant geometric deep leanring to predict the binding site and conformation of the ligand bound to a given protein. While the model is fast compared to many commercial tools, but the model seems to perform poorly under 2 Å. The authors developed a follow up paper, DiffDock, that uses a diffusion model accomplish the same task. 