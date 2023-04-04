Personal repository for making molecular dynamics datasets for butane.

Needed libraries (will add version specifity later):

**Recent Additions**: 
- Openmm scripts for getting data at high temperature, and for metadynamics (see `scripts/')
- .npz files for high temp and metadynamics datasets

For running 'script/main.ipynb' to show the collected numpy data on butane:
- NumPy
- Pyplot

For running 'script/butane_openmm.ipynb' to mess with the butane data generation in openmm, the additional libraries are needed:
- MDTraj
- OpenMM
- tqdm

Most of the openmm code is adapted from the [FastMBAR example for computing the potential of mean force for butane](https://fastmbar.readthedocs.io/en/latest/butane_PMF.html).