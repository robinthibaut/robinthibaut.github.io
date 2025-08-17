---
layout: page
title: SKBEL
description: Bayesian Evidential Learning framework built on top of scikit-learn
img: assets/img/publication_preview/whpa.png
importance: 1
category: software
related_publications: true
---

## SKBEL: Bayesian Evidential Learning Framework

**SKBEL** is a Python framework for **Bayesian Evidential Learning (BEL)** built on top of scikit-learn. It provides tools for experimental design and uncertainty quantification in geosciences and engineering applications.

### Key Features

- **Bayesian Experimental Design**: Minimize posterior uncertainty by optimally selecting measurement locations
- **Integration with scikit-learn**: Leverage the extensive ML ecosystem while maintaining scientific rigor
- **Geoscience Applications**: Specifically designed for subsurface characterization and monitoring
- **Open Source**: Fully documented and maintained on GitHub

### Applications

The framework has been successfully applied to:

- **Wellhead Protection Area Design**: Optimizing monitoring well placement for groundwater protection
- **Temperature Monitoring**: Comparing wells vs. geophysical data for 4D temperature field monitoring
- **Subsurface Characterization**: General framework for any inverse problem requiring uncertainty quantification

### Technical Details

SKBEL implements the theoretical framework developed during my PhD research, providing:

- Efficient posterior sampling using surrogate models
- Information-theoretic experimental design criteria
- Integration with various forward models
- Visualization and analysis tools

### Publications

This work has resulted in peer-reviewed publications in:
- *Journal of Hydrology* (2021): Framework development and wellhead protection applications
- *Water Resources Research* (2022): Comparison of well and geophysical data for temperature monitoring

### Repository

**GitHub**: [github.com/robinthibaut/skbel](https://github.com/robinthibaut/skbel)  
**DOI**: [10.5281/zenodo.6205242](https://doi.org/10.5281/zenodo.6205242)  
**Documentation**: Available in the repository
