# OpenSBFEM-TO

**OpenSBFEM-TO** is an open-source MATLAB framework for three-dimensional topology optimization based on the scaled boundary finite element method (SBFEM). The framework is designed to read STL geometry, construct an octree-compatible SBFEM analysis model, and perform density-based compliance topology optimization with stability-guided cell consolidation.

## Current Status

This repository is currently a public placeholder for the manuscript:

> OpenSBFEM-TO: An Open-Source Framework for 3D Topology Optimization with Stability-Guided Cell Consolidation

The source code, example STL files, and running instructions will be released after the manuscript is accepted/published. This temporary repository is provided to reserve a stable project link for the paper and to make the planned code availability transparent.

## Planned Release Contents

The first public code release will include:

- `open_SBFEMTO_3D.m`, the self-contained MATLAB implementation;
- `run.m`, the user-facing demonstration script;
- example STL models used in the paper;
- plotting and result-export utilities;
- documentation for adjustable parameters and local functions;
- a tagged release corresponding to the published manuscript.

## Main Features

- STL-driven 3D topology optimization workflow;
- SBFEM analysis on octree-compatible polyhedral cells;
- SIMP-based compliance minimization with MMA update;
- stability-guided fine-to-coarse cell consolidation;
- boundary-condition protection during consolidation;
- self-contained educational MATLAB implementation.

## Code Availability

The code is not yet included in this repository because the manuscript is still under review/pre-publication preparation. The complete source code will be uploaded to this repository once the paper is accepted/published.

## Citation

Please cite the associated paper after publication. A `CITATION.cff` file and a versioned release will be added together with the source code.

## License

The open-source license will be added when the source code is released.
