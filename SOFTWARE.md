# Scientific Software Catalogue

A catalogue of widely used scientific software packages, grouped by domain. It accompanies the [Awesome SE4AISci](README.md) list. Packages that already expose an agent interface are listed in the README under [Agent-ready scientific software](README.md#agent-ready-scientific-software).

## Contents

- [Visualization, imaging and statistics](#visualization-imaging-and-statistics)
- [PDE, finite-element and multiphysics frameworks](#pde-finite-element-and-multiphysics-frameworks)
- [Materials science](#materials-science)
- [Chemistry and molecular simulation](#chemistry-and-molecular-simulation)
- [Life sciences](#life-sciences)
- [Astronomy and astrophysics](#astronomy-and-astrophysics)
- [High-energy and nuclear physics](#high-energy-and-nuclear-physics)
- [Earth and climate](#earth-and-climate)
- [Quantum computing](#quantum-computing)

## Visualization, imaging and statistics

| Name | Description | Links |
|---|---|---|
| Matplotlib | Plotting and visualization library for Python | [website](https://matplotlib.org/) [code](https://github.com/matplotlib/matplotlib) |
| ggplot2 | Implementation of the grammar of graphics in R | [website](https://ggplot2.tidyverse.org/) [code](https://github.com/tidyverse/ggplot2) |
| ParaView | Open-source, multi-platform data analysis and visualization application based on VTK | [website](https://www.paraview.org/) [code](https://github.com/Kitware/ParaView) |
| VTK | The Visualization Toolkit: open-source software for 3D computer graphics, image processing and visualization | [website](https://vtk.org/) [code](https://gitlab.kitware.com/vtk/vtk) |
| VisIt | Visualization and data analysis for mesh-based scientific data, built for very large data | [website](https://visit-dav.github.io/visit-website/) [code](https://github.com/visit-dav/visit) |
| ImageJ (and ImageJ2) | Public-domain software for processing and analysing scientific images, developed since 1997 as a cross-platform version of NIH Image | [website](https://imagej.net/software/imagej/) [code](https://github.com/imagej/ImageJ) |
| Fiji | Batteries-included distribution of ImageJ for biological image analysis | [website](https://fiji.sc/) [code](https://github.com/fiji/fiji) |
| napari | Fast, interactive, multi-dimensional image viewer for Python | [website](https://napari.org/) [code](https://github.com/napari/napari) |
| scikit-image | Image processing in Python | [website](https://scikit-image.org/) [code](https://github.com/scikit-image/scikit-image) |
| Stan | Probabilistic programming language for Bayesian statistical modeling and inference | [website](https://mc-stan.org/) [code](https://github.com/stan-dev/stan) |
| PyMC | Bayesian modeling and probabilistic programming in Python | [website](https://www.pymc.io/) [code](https://github.com/pymc-devs/pymc) |
| lme4 | Mixed-effects models in R using S4 classes and methods with RcppEigen | [website](https://cran.r-project.org/package=lme4) [code](https://github.com/lme4/lme4) |
| ArviZ | Exploratory analysis of Bayesian models with Python | [website](https://python.arviz.org/) [code](https://github.com/arviz-devs/arviz) |


## PDE, finite-element and multiphysics frameworks

| Name | Description | Links |
|---|---|---|
| deal.II | Software library supporting the creation of finite element codes | [website](https://dealii.org/) [code](https://github.com/dealii/dealii) |
| FEniCS (FEniCSx and DOLFINx) | Computing platform for solving PDEs with automated finite element methods in Python and C++ (components include UFL, Basix and DOLFINx) | [website](https://fenicsproject.org/) [code](https://github.com/FEniCS/dolfinx) |
| Firedrake | Automated system for the portable solution of partial differential equations using the finite element method, with PETSc solvers | [website](https://www.firedrakeproject.org/) [code](https://github.com/firedrakeproject/firedrake) |
| MFEM | Lightweight, general, scalable C++ library for finite element methods | [website](https://mfem.org/) [code](https://github.com/mfem/mfem) |
| MOOSE | Multiphysics Object Oriented Simulation Environment for massively parallel multiphysics simulation | [website](https://mooseframework.inl.gov/) [code](https://github.com/idaholab/moose) |
| OpenFOAM | Free, open-source C++ software for computational fluid dynamics, released by the OpenFOAM Foundation (a separate ESI-OpenCFD distribution lives at openfoam.com) | [website](https://openfoam.org/) [code](https://github.com/OpenFOAM/OpenFOAM-dev) |
| preCICE | Coupling library for partitioned multi-physics and multi-scale simulations | [website](https://precice.org/) [code](https://github.com/precice/precice) |
| Gmsh | Three-dimensional finite element mesh generator with built-in pre- and post-processing facilities | [website](https://gmsh.info/) [code](https://gitlab.onelab.info/gmsh/gmsh) |


## Materials science

| Name | Description | Links |
|---|---|---|
| VASP | Plane-wave projector augmented-wave DFT package for materials, licensed by VASP Software GmbH | [website](https://www.vasp.at) |
| Quantum ESPRESSO | Open-source suite of plane-wave pseudopotential DFT codes for electronic-structure calculations and materials modelling | [website](https://www.quantum-espresso.org) [code](https://gitlab.com/QEF/q-e) |
| CP2K | Quantum chemistry and solid-state physics package centred on DFT with the mixed Gaussian and plane-wave (Quickstep) method and ab initio molecular dynamics | [website](https://www.cp2k.org) [code](https://github.com/cp2k/cp2k) |
| ABINIT | Plane-wave DFT, density-functional perturbation theory and many-body perturbation theory package for solids and nanostructures | [website](https://www.abinit.org) [code](https://github.com/abinit/abinit) |
| GPAW | Python code for DFT and beyond within the projector augmented-wave method, developed alongside ASE | [website](https://gpaw.readthedocs.io) [code](https://gitlab.com/gpaw/gpaw) |
| ASE | Atomic Simulation Environment: Python library for working with atoms, building structures and driving many simulation codes through a common calculator interface | [website](https://ase-lib.org) [code](https://gitlab.com/ase/ase) |
| pymatgen | Python Materials Genomics library for structure manipulation, materials analysis and input/output for many simulation codes | [website](https://pymatgen.org) [code](https://github.com/materialsproject/pymatgen) |
| atomate2 | Modular library of computational materials science workflows (successor generation of atomate) | [website](https://materialsproject.github.io/atomate2/) [code](https://github.com/materialsproject/atomate2) |
| phonopy | Phonon calculation package with interfaces to VASP, Quantum ESPRESSO, ABINIT, LAMMPS and other codes | [website](https://phonopy.github.io/phonopy/) [code](https://github.com/phonopy/phonopy) |
| Materials Project | Open database of computed materials properties with a REST API client (mp-api) and web apps | [website](https://materialsproject.org) [code](https://github.com/materialsproject/api) |
| AFLOW | Automatic framework for high-throughput materials discovery (aflow++) and the aflow.org database ecosystem | [website](https://aflow.org) [code](https://github.com/aflow-org/aflow) |
| NOMAD | FAIR research-data management platform and repository for materials science, deployable locally as NOMAD Oasis | [website](https://nomad-lab.eu) [code](https://github.com/FAIRmat-NFDI/nomad) |
| OpenKIM | Open Knowledgebase of Interatomic Models with tests, verification checks and the KIM API | [website](https://openkim.org) [code](https://github.com/openkim/kim-api) |
| MACE | Higher-order equivariant message-passing interatomic potentials, including the MACE-MP foundation models | [website](https://mace-docs.readthedocs.io) [code](https://github.com/ACEsuit/mace) |
| NequIP | Framework for E(3)-equivariant interatomic potentials, with the Allegro architecture for scalable MD (major backwards-incompatible v0.7 rewrite in April 2025) | [website](https://nequip.readthedocs.io) [code](https://github.com/mir-group/nequip) |
| DeePMD-kit | Deep Potential package for many-body potential energy representation and ML-driven molecular dynamics, with multiple deep-learning backends in v3 | [website](https://docs.deepmodeling.com/projects/deepmd/) [code](https://github.com/deepmodeling/deepmd-kit) |
| Matbench Discovery | Evaluation framework ranking machine-learning interatomic potentials on high-throughput materials discovery | [website](https://matbench-discovery.materialsproject.org) [code](https://github.com/janosh/matbench-discovery) |


## Chemistry and molecular simulation

| Name | Description | Links |
|---|---|---|
| GROMACS | High-performance molecular dynamics toolkit designed primarily for biomolecular systems | [website](https://www.gromacs.org) [code](https://gitlab.com/gromacs/gromacs) |
| LAMMPS | Classical molecular dynamics code for particle-based materials modeling at the atomic, meso and continuum scales | [website](https://www.lammps.org) [code](https://github.com/lammps/lammps) |
| AMBER | Biomolecular simulation package distributed as the AmberTools suite plus the Amber MD engine | [website](https://ambermd.org) |
| NAMD | Parallel molecular dynamics code for large biomolecular systems on CPUs and GPUs | [website](https://www.ks.uiuc.edu/Research/namd/) [code](https://gitlab.com/tcbgUIUC/namd) |
| OpenMM | Toolkit for GPU-accelerated molecular simulation with a Python API and support for machine-learning potentials | [website](https://openmm.org) [code](https://github.com/openmm/openmm) |
| CHARMM | General-purpose biomolecular simulation program for energy minimization and molecular dynamics | [website](https://academiccharmm.org) |
| PLUMED | Community-developed plugin library for enhanced sampling and free-energy methods that works with many MD engines | [website](https://www.plumed.org) [code](https://github.com/plumed/plumed2) |
| Gaussian | Commercial general-purpose electronic-structure program | [website](https://gaussian.com) |
| ORCA | General-purpose quantum chemistry package with DFT, wavefunction methods and spectroscopy | [website](https://www.faccts.de/orca/) |
| Psi4 | Open-source quantum chemistry package with a C++ core driven by Python, aimed at high-throughput and automated workflows | [website](https://psicode.org) [code](https://github.com/psi4/psi4) |
| PySCF | Python module for quantum chemistry (the Python-based simulations of chemistry framework) | [website](https://pyscf.org) [code](https://github.com/pyscf/pyscf) |
| NWChem | Open-source high-performance computational chemistry package covering Gaussian-basis and plane-wave DFT, coupled cluster, QM/MM and molecular dynamics | [website](https://nwchemgit.github.io) [code](https://github.com/nwchemgit/nwchem) |
| xtb | Semiempirical extended tight-binding program (GFN-xTB methods) for fast quantum chemistry of large molecules | [website](https://xtb-docs.readthedocs.io) [code](https://github.com/grimme-lab/xtb) |
| RDKit | Open-source cheminformatics toolkit with a C++ core and Python bindings | [website](https://www.rdkit.org) [code](https://github.com/rdkit/rdkit) |
| Open Babel | Chemical toolbox for converting, searching and analysing data across many chemical file formats | [website](https://openbabel.org) [code](https://github.com/openbabel/openbabel) |
| AutoDock Vina | Molecular docking program, with new docking methods, an expanded force field and Python bindings since version 1.2.0 | [website](https://vina.scripps.edu) [code](https://github.com/ccsb-scripps/AutoDock-Vina) |
| MDAnalysis | Python library to analyse molecular dynamics simulations | [website](https://www.mdanalysis.org) [code](https://github.com/MDAnalysis/mdanalysis) |
| OVITO | Scientific visualization and analysis software for atomistic and particle simulation data | [website](https://www.ovito.org) [code](https://gitlab.com/stuko/ovito) |
| VMD | Molecular visualization and analysis program for biomolecular systems and MD trajectories, with modular, extensible C++ source code | [website](https://www.ks.uiuc.edu/Research/vmd/) |
| PyMOL | User-sponsored molecular visualization system from Schrödinger with an open-source foundation | [website](https://pymol.org) [code](https://github.com/schrodinger/pymol-open-source) |
| VESTA | Three-dimensional visualization program for crystal structures, volumetric data and crystal morphologies, free for non-commercial users (latest 3.5.8, August 2022) | [website](https://jp-minerals.org/vesta/en/) |


## Life sciences

| Name | Description | Links |
|---|---|---|
| BLAST (NCBI BLAST+) | Local alignment search of nucleotide and protein sequences against databases, distributed by NCBI as the BLAST+ command-line suite | [website](https://blast.ncbi.nlm.nih.gov/) |
| SAMtools and BCFtools | Utilities for SAM/BAM/CRAM and VCF/BCF manipulation, sorting, statistics, variant calling and effect analysis (BCFtools lives at github.com/samtools/bcftools) | [website](https://www.htslib.org/) [code](https://github.com/samtools/samtools) |
| BWA | Burrows-Wheeler Aligner for mapping DNA sequencing reads against a reference genome | [website](https://bio-bwa.sourceforge.net/) [code](https://github.com/lh3/bwa) |
| STAR | Spliced aligner for mapping RNA-seq reads to a reference genome using uncompressed suffix arrays | [code](https://github.com/alexdobin/STAR) |
| GATK | Toolkit for variant discovery and genotyping from high-throughput sequencing data | [website](https://gatk.broadinstitute.org/) [code](https://github.com/broadinstitute/gatk) |
| DESeq2 | Differential gene expression analysis of count data based on the negative binomial distribution | [website](https://bioconductor.org/packages/DESeq2) [code](https://github.com/thelovelab/DESeq2) |
| Bioconductor | Open-source project distributing R packages for the analysis of high-throughput genomic data | [website](https://bioconductor.org/) [code](https://github.com/Bioconductor) |
| Biopython | Collection of Python tools for computational molecular biology and bioinformatics | [website](https://biopython.org/) [code](https://github.com/biopython/biopython) |
| Scanpy | Scalable Python toolkit for preprocessing, visualization, clustering and analysis of single-cell gene expression data | [website](https://scanpy.scverse.org/) [code](https://github.com/scverse/scanpy) |
| Seurat | R toolkit for quality control, analysis, integration and exploration of single-cell genomics data | [website](https://satijalab.org/seurat/) [code](https://github.com/satijalab/seurat) |
| CellProfiler | Open-source application for modular, high-throughput quantitative analysis of biological images | [website](https://cellprofiler.org/) [code](https://github.com/CellProfiler/CellProfiler) |
| AlphaFold 2 | Deep learning system predicting protein 3D structures and complexes from amino acid sequences | [website](https://deepmind.google/science/alphafold/) [code](https://github.com/google-deepmind/alphafold) |
| AlphaFold 3 | Inference pipeline predicting complexes of proteins, nucleic acids, ligands, ions and modified residues | [website](https://deepmind.google/science/alphafold/) [code](https://github.com/google-deepmind/alphafold3) |
| Rosetta | Software suite for macromolecular structure prediction, docking and design | [website](https://rosettacommons.org/) [code](https://github.com/RosettaCommons/rosetta) |
| RELION | Bayesian (maximum a posteriori) image processing for cryo-EM single-particle analysis and subtomogram averaging | [website](https://relion.readthedocs.io/en/latest/) [code](https://github.com/3dem/relion) |
| Phenix | Integrated suite for macromolecular structure determination from X-ray, neutron, electron and cryo-EM data | [website](https://phenix-online.org/) |
| UCSF ChimeraX | Successor to UCSF Chimera for visualization and analysis of atomic structures, density maps and sequences, with virtual and augmented reality support | [website](https://www.cgl.ucsf.edu/chimerax/) [code](https://github.com/RBVI/ChimeraX) |
| NEURON | Simulator for neurons and networks of neurons on local machines, cloud or HPC | [website](https://www.neuronsimulator.org/) [code](https://github.com/neuronsimulator/nrn) |
| FSL | Library of analysis tools for functional, structural and diffusion MRI brain imaging data | [website](https://fsl.fmrib.ox.ac.uk/fsl/docs/) [code](https://git.fmrib.ox.ac.uk/fsl) |
| FreeSurfer | Suite for structural MRI analysis, including cortical surface reconstruction and brain segmentation | [website](https://surfer.nmr.mgh.harvard.edu/) [code](https://github.com/freesurfer/freesurfer) |
| fMRIPrep | Robust preprocessing pipeline for functional MRI data | [website](https://fmriprep.org/) [code](https://github.com/nipreps/fmriprep) |
| SPM | Software for statistical parametric mapping, testing hypotheses about brain structure and function from imaging data | [website](https://www.fil.ion.ucl.ac.uk/spm/) [code](https://github.com/spm/spm) |
| PK-Sim | Whole-body physiologically based pharmacokinetic (PBPK) modelling software from the Open Systems Pharmacology Suite | [website](https://www.open-systems-pharmacology.org/) [code](https://github.com/Open-Systems-Pharmacology/PK-Sim) |


## Astronomy and astrophysics

| Name | Description | Links |
|---|---|---|
| Astropy | Community-developed core Python package providing common functionality for astronomy | [website](https://www.astropy.org/) [code](https://github.com/astropy/astropy) |
| yt | Analysis and visualization toolkit for volumetric data, notably multi-code astrophysical simulations | [website](https://yt-project.org/) [code](https://github.com/yt-project/yt) |
| CASA | Primary data processing software for radio telescopes including ALMA and the VLA | [website](https://casa.nrao.edu/) [code](https://open-bitbucket.nrao.edu/projects/CASA/repos/casa6/browse) |
| HEALPix | Hierarchical equal-area isolatitude pixelization for fast analysis of data on the sphere | [website](https://healpix.sourceforge.io/) [code](https://sourceforge.net/projects/healpix/) |
| emcee | Affine-invariant ensemble MCMC sampler implementing the Goodman and Weare algorithm | [website](https://emcee.readthedocs.io/) [code](https://github.com/dfm/emcee) |
| CAMB | Code for CMB angular power spectra, matter transfer functions and background cosmology | [website](https://camb.info/) [code](https://github.com/cmbant/CAMB) |
| CLASS | Boltzmann code for linear cosmological perturbations and CMB anisotropy spectra | [website](http://class-code.net) [code](https://github.com/lesgourg/class_public) |
| GADGET | Parallel cosmological N-body and SPH code for cosmic structure formation and galaxy evolution (GADGET-4 succeeds GADGET-2) | [website](https://wwwmpa.mpa-garching.mpg.de/gadget4/) [code](https://gitlab.mpcdf.mpg.de/vrs/gadget4) |
| MESA | Modules for Experiments in Stellar Astrophysics, open-source libraries and a one-dimensional stellar evolution code | [website](https://docs.mesastar.org/) [code](https://github.com/MESAHub/mesa) |


## High-energy and nuclear physics

| Name | Description | Links |
|---|---|---|
| ROOT | Framework for storing, analysing and visualizing large scientific datasets, with a C++ interpreter and Python bindings | [website](https://root.cern/) [code](https://github.com/root-project/root) |
| Geant4 | Toolkit for simulating the passage of particles through matter, used in detector, medical and space applications | [website](https://geant4.web.cern.ch/) [code](https://github.com/Geant4/geant4) |
| Pythia | General-purpose event generator for high-energy collisions, covering hard processes, parton showers, multiparton interactions and Lund string hadronization | [website](https://pythia.org/) [code](https://gitlab.com/Pythia8/releases) |
| MadGraph5_aMC@NLO | Framework for automated tree-level and NLO cross sections and event generation matched to parton showers | [website](https://launchpad.net/mg5amcnlo) [code](https://github.com/mg5amcnlo/mg5amcnlo) |
| Sherpa | General-purpose Monte Carlo event generator for high-energy particle collisions with matrix elements, parton showers and multijet merging | [website](https://sherpa-team.gitlab.io/) [code](https://gitlab.com/sherpa-team/sherpa) |
| Rivet | Toolkit and library of preserved collider analyses for validating and tuning Monte Carlo event generators | [code](https://gitlab.com/hepcedar/rivet) |
| uproot | Reader and writer for ROOT files in pure Python and NumPy, without a ROOT dependency | [website](https://uproot.readthedocs.io/) [code](https://github.com/scikit-hep/uproot5) |
| pyhf | Pure-Python implementation of HistFactory binned statistical models with tensor backends and automatic differentiation | [website](https://pyhf.readthedocs.io/) [code](https://github.com/scikit-hep/pyhf) |


## Earth and climate

| Name | Description | Links |
|---|---|---|
| CESM | Community Earth System Model coupling atmosphere, ocean, land, sea-ice and land-ice components for climate research | [website](https://www.cesm.ucar.edu/) [code](https://github.com/ESCOMP/CESM) |
| E3SM | DOE Energy Exascale Earth System Model for high-resolution coupled Earth system simulation on DOE supercomputers | [website](https://e3sm.org/) [code](https://github.com/E3SM-Project/E3SM) |
| WRF | Mesoscale numerical weather prediction and atmospheric research model with the Advanced Research WRF dynamical core | [website](https://www2.mmm.ucar.edu/wrf/site/) [code](https://github.com/wrf-model/WRF) |
| NEMO | Nucleus for European Modelling of the Ocean, a framework for ocean dynamics, sea ice and biogeochemistry used in research and operational forecasting | [website](https://www.nemo-ocean.eu/) [code](https://forge.nemo-ocean.eu/nemo/nemo) |
| ESMValTool | Community diagnostics and performance-metrics tool for routine evaluation of Earth system models, for example in CMIP | [website](https://esmvaltool.org/) [code](https://github.com/ESMValGroup/ESMValTool) |
| GDAL | Translator library and utilities for raster and vector geospatial data formats | [website](https://gdal.org/) [code](https://github.com/OSGeo/gdal) |
| QGIS | Free and open-source cross-platform desktop geographic information system for viewing, editing and analysing geospatial data | [website](https://qgis.org/) [code](https://github.com/qgis/QGIS) |
| Iris | Format-agnostic, community-driven Python package for analysing and visualising Earth science data | [website](https://scitools-iris.readthedocs.io/) [code](https://github.com/SciTools/iris) |


## Quantum computing

| Name | Description | Links |
|---|---|---|
| Qiskit | Open-source SDK for building, transpiling and executing quantum circuits on simulators and IBM quantum hardware | [website](https://www.ibm.com/quantum/qiskit) [code](https://github.com/Qiskit/qiskit) |
| Cirq | Python framework for creating, editing and running noisy intermediate-scale quantum (NISQ) circuits on simulators and hardware | [website](https://quantumai.google/cirq) [code](https://github.com/quantumlib/Cirq) |
| PennyLane | Library for differentiable programming of quantum computers, quantum machine learning and quantum chemistry | [website](https://pennylane.ai/) [code](https://github.com/PennyLaneAI/pennylane) |
| QuTiP | Quantum Toolbox in Python for simulating the dynamics of open and closed quantum systems | [website](https://qutip.org/) [code](https://github.com/qutip/qutip) |
| Stim | Fast simulator for quantum stabilizer circuits, widely used in quantum error-correction research | [code](https://github.com/quantumlib/Stim) |

## License

[CC BY 4.0](LICENSE).
