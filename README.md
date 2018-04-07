# ASE-ANI

### NOTICE: Python binaries built for python 3.6 and CUDA 9
### Works only under Ubuntu variants of Linux 

This is a prototype interface for ANI-1 neural net potential for The Atomic Simulation Environment (ASE). Current ANI-1.1 potential implements CHNO elements.

##REQUIREMENTS:
* Python 3.6 (we recommend [Anaconda](https://www.continuum.io/downloads) distribution)
* [CUDA 9.0](https://developer.nvidia.com/cuda-downloads)
* [ASE](https://wiki.fysik.dtu.dk/ase/index.html)
* Modified [ased3](https://github.com/isayev/ased3) for D3 van der Waals correction (Optional) 
* MOPAC2012 or MOPAC2016 for some examples to compare results (Optional) 

## Installation
Clone this repository into desired folder and add environmental variables from `bashrc_example.sh` to your `.bashrc`. 

For use cases please refer to examples folder with several iPython notebooks

## Data
https://github.com/isayev/ANI1_dataset

## Benchmark
https://github.com/isayev/COMP6

## Citation
If you use this code, please cite:

### ML Potential Method:
Justin S. Smith, Olexandr Isayev, Adrian E. Roitberg. *ANI-1: An extensible neural network potential with DFT accuracy at force field computational cost*. Chemical Science, 2017, DOI: [10.1039/C6SC05720A](http://pubs.rsc.org/en/content/articlelanding/2017/sc/c6sc05720a)

### Original data:
Justin S. Smith, Olexandr Isayev, Adrian E. Roitberg. ANI-1, A data set of 20 million calculated off-equilibrium conformations for organic molecules. Scientific Data, 4, Article number: 170193, DOI: 10.1038/sdata.2017.193 https://www.nature.com/articles/sdata2017193

### Active-learning based data:
Justin S. Smith, Ben Nebgen, Nicholas Lubbers, Olexandr Isayev, Adrian E. Roitberg. *Less is more: sampling chemical space with active learning*. arXiv, 2018, DOI: [arXiv:1801.09319] (https://arxiv.org/abs/1801.09319)

