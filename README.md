# 🐾 MIDAS Model Zoo 🐾

The **MIDAS Model Zoo** is a growing open-source library of AI and data science tools, datasets, and models developed by researchers at the [Michigan Institute for Data & AI in Society (MIDAS)](https://midas.umich.edu) — ready to use for **research, teaching, and applied projects**.

Browse pre-trained models with example usage, reproducible workflows, and documentation spanning a wide range of domains, including healthcare, environmental science, education, geospatial analysis, and more. All contributions are welcome!

---

## Table of Contents
- [Software](#available-software)
- [Tutorials](#tutorials)
- [Datasets](#datasets)
- [Web Applications](#web-applications)
- [Models](#models)
---

## Software
| Software | Domain | Description | Software Link | Additional links | Creator |
|-------|--------|------|-----|------|-----|
| `PyStarshade` | Astrophysics | PyStarshade is a Python library for Starshade (or any external occulter) simulations from star-planet system to CCD with Fresnel diffraction methods. This library efficiently calculates output fields using Bluestein FFTs. | [Repo](https://github.com/xiaziyna/PyStarshade) |[Paper](https://joss.theoj.org/papers/10.21105/joss.07917) |Jamila Taaki (MIDAS AI Fellow)
| `isweep` | Statistical inference | Python package and a series of automated workflows to study natural selection with identity-by-descent (IBD) segments. The Python package simulates IBD segments around a locus and estimates selection coefficients. | [Repo](https://github.com/sdtemple/isweep) |[Paper](https://www.cell.com/ajhg/fulltext/S0002-9297(24)00333-1) [Paper 2](https://link.springer.com/article/10.1007/s11538-025-01464-8) [Paper 3](https://www.cell.com/ajhg/fulltext/S0002-9297(25)00360-X) [Paper 4](https://www.cell.com/ajhg/fulltext/S0002-9297(26)00035-2) |Seth Temple (MIDAS AI Fellow)
| `peirrs` | Statistical inference | R package for Pair-based Estimators of Infection and Removal Rates. Estimate infection and removal rates with partially observed removal and infection times. The following functions are the ones you would likely use, in order of relevance. | [Repo](https://github.com/sdtemple/isweep) |[Paper](https://arxiv.org/abs/2603.21992) |Seth Temple (MIDAS AI Fellow)
| `bifrost` | Evolution | Branch-level Inference Framework for Recognizing Optimal Shifts in Traits bifrost performs branch-level inference of multi-regime, multivariate trait evolution on a phylogeny using penalized-likelihood multivariate GLS fits.  | [Repo](https://github.com/jakeberv/bifrost) |[Cran](https://cran.r-project.org/web/packages/bifrost/index.html) |	Jacob Berv (MIDAS AI Fellow alum)
| `PPGISr` | GIS | An R package for public participatory GIS | [Repo](https://github.com/GLISA-umich/PPGISr) | [Paper](https://www.sciencedirect.com/science/article/pii/S2352711023000857) |	Derek Van Berkel (MIDAS Faculty Affiliate)
| `Urban-Worm` | Urban Planning | Urban-Worm is a Python library that integrates remote sensing imagery, street view data, and vision-language models (VLMs) to assess urban units. Using APIs for data collection and VLMs for inference, Urban-Worm is designed to support the automation of the evaluation for urban environments, including roof integrity, structural condition, landscape quality, and urban perception. | [Repo](https://github.com/land-info-lab/urbanworm) | [Documentation](https://land-info-lab.github.io/urbanworm/) |	Xiaohao Yang (SEAS PhD Student)
| `Viewscape` | GIS |An R package for the spatial analysis of landscape perception and configurations in viewsheds of landscapes| [Repo](https://github.com/land-info-lab/viewscape) | [Paper](https://www.sciencedirect.com/science/article/pii/S2352711024000335) |	Xiaohao Yang (SEAS PhD Student)


---

## Tutorials
| Tutorial | Link | Creator |
|------------|--------|------|
| **`Fitting PyTorch models`** | [GitHub](https://github.com/sdtemple/zootopia3) | Seth Temple (MIDAS AI Fellow)

---

## Datasets
| Dataset| Domain | Task | Link | Creator |
|------------|--------|------|------|---|
| **`AI validated plant observations from social media`** | Ecology | Plant Image Classification | [Zenodo](https://zenodo.org/records/3514685) | Nathan Fox (MIDAS Staff)

---

## Web Applications
| Model | Use| Website | Creator |
|------------|--------|------|------|
| **`Clinical Trial Randomization Tool`** | Clinical Trials. Provides balanced assignments across pre-treatment covariates even with small sample sizes, making it effective for both small and moderate enrollment targets. | [Website](https://ctrt.midas.umich.edu/) | Kerby Shedden (MIDAS Faculty Affiliate)

---

## Models
| Model | Task | Link |Creator|
|------------|------|------|-----|
| **`color-prediction-model`** |  Image Classification - predicts the color (among 8 colors) of 1 shape (circle, rectangle, diamond, triangle) in a 224 x 224 x 3 image. | [Hugging Face Link](https://huggingface.co/sdtemple/color-prediction-model) | Seth Temple (MIDAS AI Fellow)
| **`shape-prediction-model`** |  Image Classification - predicts the shape (circle, rectangle, diamond, or triangle) of the 1 colored shape (8 colors) in a 224 x 224 x 3 image. | [Hugging Face Link](https://huggingface.co/sdtemple/shape-prediction-model) | Seth Temple (MIDAS AI Fellow)

---


