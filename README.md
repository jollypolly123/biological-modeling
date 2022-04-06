# Biological Modeling Practice Exercises

From https://biologicalmodeling.org/

### [Prologue](https://github.com/jollypolly123/biological-modeling/tree/main/module-0)

- [x] Simulating particle diffusion
- [x] Generating Turing patterns with a reaction-diffusion particle simulation
- [x] Building a diffusion cellular automaton
- [x] Implementing the Gray-Scott reaction-diffusion automaton

### [Module 1](https://github.com/jollypolly123/biological-modeling/tree/main/module-1)

- [x] Hunting for loops in transcription factor networks
- [x] Comparing simple regulation to negative autoregulation
- [x] Ensuring a mathematically controlled simulation for comparing simple regulation to negative autoregulation
- [x] Implementing the feed-forward loop motif
- [x] Implementing the repressilator
- [x] Perturbing the represillator

### [Module 2](https://github.com/jollypolly123/biological-modeling/tree/main/module-2)

- [x] Getting started with BioNetGen and modeling ligand-receptor dynamics
- [x] Adding phosphorylation to our BioNetGen model
- [x] Modeling bacterial adaptation to changing attractant
- [x] Traveling up an attractant gradient
- [x] Traveling down an attractant gradient
- [x] Modeling a pure random walk strategy
- [x] Modeling E. coli's sophisticated random walk algorithm
- [ ] Comparing different chemotaxis default tumbling frequencies

### Module 3

- [ ] Using ab initio modeling to predict the structure of hemoglobin subunit alpha
- [ ] Using homology modeling to predict the structure of the SARS-CoV-2 spike protein
- [ ] Using RMSD to compare the predicted SARS-CoV-2 spike protein against its experimentally validated structure
- [ ] Finding local differences in the SARS-CoV and SARS-CoV-2 spike protein structures
- [ ] Visualizing specific regions of interest within the spike protein structure
- [ ] Computing the energy contributed by a local region of the SARS-CoV-2 spike protein bound with the human ACE2 enzyme
- [ ] Analyzing coronavirus spike proteins using GNM
- [ ] Adding directionality to spike protein GNM simulations using ANM
- [ ] Integrating molecular dynamics analyses with DynOmics

### Module 4

- [ ] Segmenting nuclei from cellular images
- [ ] Generating and visualizing an image shape space after applying PCA
- [ ] Training a classifier on an image shape space

## Setup

Run `pip -r requirements.txt` (as you do) for Python-related things  
If you want to open `.blend` files, you'll need to have [Blender](https://www.blender.org/) installed.

### MCell and CellBlender

Download from the [homepage](https://mcell.org/download_previous.html).

### BioNetGen

For each `.bngl` file, run it by using the following command:

```shell
bionetgen run -i <input_file>.bngl
```

Then plot the results to get a `.png` file using either of the following commands:

```shell
bionetgen plot -i <input_file>.gdat
```

```shell
bionetgen plot -i <input_file>.cdat
```
