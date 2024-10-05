# OpenKMI GitHub

## Overview
The [Open Kinetic Modeling Initiative (OpenKMI)](https://www.openkmi.org/) is an open-source effort aimed at accelerating research and educational opportunities in tracer kinetic modeling for molecular imaging. Tracer kinetic modeling allows for quantitative characterization of molecular processes, such as those involved in cancer and other major diseases. While the field has seen extensive research over the years, its clinical adoption has been limited by technological constraints in PET scanner performance. With advancements such as total-body PET and other long axial field-of-view PET scanners, there is a renewed interest in pushing kinetic modeling forward, and the need for accessible resources has never been greater. OpenKMI seeks to meet this need by offering robust, open-source solutions that make kinetic modeling more accessible to both experienced researchers and newcomers. 

## OpenKMAP: an OpenKMI code project

**KMAP (Kinetic Modeling and Analysis Package)** offers a collection of C/C++ source code and wrapper functions designed to implement and apply different tracer kinetic models for analyzing dynamic positron emission tomography (PET) data, particularly in response to the challenges emerging in total-body PET kinetic modeling. The package was originally developed at the University of California, Davis. Its open-source version, **OpenKMAP**, is launched as a part of the OpenKMI. The primary objective of this open-source package is to share tracer kinetic modeling techniques and offer kinetic modeling developers a foundation to build upon without starting from scratch. 

<img align="left" src="https://github.com/user-attachments/assets/dc93ccfc-7ab0-4cde-b3f4-aeabd3562033" width="500" >

As part of OpenKMAP, two key packages are currently provided:

- **[C-KMAP](https://github.com/OpenKMI/C-KMAP):** A C/C++ toolkit that provides a suite of routines for implementing various tracer kinetic models. These include source code and MEX files that enable integration with other software, such as MATLAB.
  
- **[M-KMAP](https://github.com/OpenKMI/M-KMAP):** A MATLAB toolbox built on top of C-KMAP. This toolbox provides a user-friendly interface for performing kinetic modeling and analysis using MATLAB, with support for multiple operating systems including Windows, Linux, and macOS.

Together, C-KMAP and M-KMAP offer a solution for researchers in tracer kinetic modeling, providing both the low-level computational tools and the high-level MATLAB functionality.

**Ongoing Efforts**: Both packages are continually being updated. The development team is working on adding new models, optimizing performance, and expanding the functionality of both C-KMAP and M-KMAP. The packages are provided “as is” without warranty, but contributions from the community are highly encouraged to improve and expand the tools.

## OpenIFun: an OpenKMI data project

OpenIFun is an open-data project aiming to build a database of blood input functions for tracer kinetic modeling of dynamic PET data. The first effort focuses on using total-body PET scanners to acquire image-derived input functions (IDIF) from major blood pools and plans to collect from dynamic FDG-PET scans of 200 human subjects across multiple institutions.

## Contributing
We welcome contributions from the community! Whether you’d like to suggest improvements, report bugs, or contribute code, we encourage you to get involved. Please refer to the contribution guidelines in each repository for more details.

