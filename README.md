Latent Space Simulators (LSS)
==============================

This repository demonstrates application of latent space simulators in PyTorch for two exemplar biomolecules alanine dipeptide (ADP) and the WLALL pentapeptide.

Jupyter notebooks demonstrating the LSS workflow can be found in `ADP_backbone_LSS.ipynb` and `WLALL_backbone_LSS.ipynb`

Getting Started
===============

Usage
------------
To run the examples you will need to clone and install the following repositories that impliment the three separate supervised learning components in your environment:

* [SNRV Encoder](https://github.com/andrewlferguson/snrv)
* [MDN Propagator](https://github.com/Ferg-Lab/mdn_propagator)
* [GAN/DDPM Decoder](https://github.com/Ferg-Lab/molgen)

Some additional dependencies for running and visualizing the examples:

* [NumPy](https://numpy.org/install/)
* [MDTraj](https://www.mdtraj.org/1.9.8.dev0/installation.html)
* [NGLView](https://github.com/nglviewer/nglview#installation)
