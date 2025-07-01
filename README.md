# NUCLEATE: Numerical models and Algorithms for High Performance Structural Mechanics

**Funded by**: Spanish Ministry of Science and Innovation  
**Who**: Israel G. García (IP) (Universidad de Sevilla), Adrià Quintanas-Corominas (Barcelona Supercomputing Center), Ricard Borrell (Former co-IP) (Barcelona Supercomputing Center), 

## Overview

**NUCLEATE** is a coordinated research project aiming to advance in finite element (FE) simulations in structural mechanics through the development of novel algorithms, numerical models, and high-performance computing (HPC) software. The goal is to unlock (pre)Exascale capabilities for simulating complex phenomena like fracture and fatigue in advanced materials.

## Objectives

### General Goals
1. **GO1**: Develop an advanced simulation framework combining cutting-edge software, scalable solvers, and robust numerical models.
2. **GO2**: Apply this framework to two demonstrator cases involving highly non-linear structural behavior:
   - Fatigue fracture in **endovascular stents** (TRL-oriented).
   - Multiscale failure in **thermoplastic composites** (high-resolution simulations).

### Specific Objectives
- **O1**: Development of Exascale-capable simulation software.
- **O2**: Scalable and robust linear/non-linear solvers.
- **O3**: Advanced material models including phase-field approaches for fracture and fatigue.
- **O4**: Study of failure across scales in thermoplastic composites.
- **O5**: Simulation of fracture and fatigue in endovascular stents.

## Key Technologies

- **Preconditioning & Krylov solvers**: Tailored for Exascale architectures.
- **Phase-field models**: For simulating fracture and fatigue in nonlinear materials.
- **Jacobain-Free Newton-Krylov Methods**: To avoid expensive Jacobian evaluations.
- **Multiscale modeling**: To connect microscale phenomena with macroscopic behavior.

## Research Impact

NUCLEATE contributes to:
- The advancement of HPC-based simulation methods aligned with the European Strategic Research Agenda for HPC.
- Environmental sustainability via improved modeling of recyclable **thermoplastic composites**.
- Biomedical innovation through patient-specific modeling of **cardiovascular stents**.

## Data & Code Availability

All simulation data and code generated under this project will be shared in **open formats** (e.g., plain text, VTK) and made accessible through public repositories following **FAIR principles**. The repository will include:
- Kernel repository with validated modules.
- Objective-specific subdirectories.
- Benchmark datasets and test cases.

## Citation

Please cite the project or associated publications when using code or data from this repository. A `CITATION.cff` file will be added soon.

## License

To be determined (MIT/GPL/Academic Free License). This section will be updated accordingly.

## Acknowledgments

This project is funded by the **Spanish Ministry of Research** under the call “Proyectos de I+D+i 2020”.

We acknowledge the computational support from:
- **Barcelona Supercomputing Center (BSC)** and **MareNostrum V**.
- **Universidad de Sevilla**: Laboratory of Elasticity and Strength of Materials.
- **EuroHPC Joint Undertaking** and **PRACE** resources.

## Contact

- [Israel G. García (US)](israelgarcia@us.es)
- [Adrià Quintanas-Corominas (BSC)](adria.quintanas@bsc.es)
