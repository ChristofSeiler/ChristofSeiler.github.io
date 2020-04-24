---
layout: page
title: Research Projects
---

## Regression Models for Mass Cytometry

In collaboration with [Catherine Blish](https://med.stanford.edu/profiles/catherine-blish) and her [lab](https://sites.stanford.edu/blishlab/) at Stanford School of Medicine, we are investigating how NK cells can be harnessed for therapeutic purposes. We use mass cytometry to measure protein expression at single cell resolution.

Interactively reproduce and explore our analyses:

[![binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChristofSeiler/cytoeffect_binder/master?urlpath=rstudio)

* Paper on statistical methods: [arXiv](http://arxiv.org/abs/1903.07976)
* R package cytoeffect: [docs](https://christofseiler.github.io/cytoeffect/)
* R package CytoGLMM: [docs](https://christofseiler.github.io/CytoGLMM/)
* Processed data: [zenodo](https://doi.org/10.5281/zenodo.2652578)
* Talk: [zenodo](https://doi.org/10.5281/zenodo.3524019)
* Posters: [zenodo](https://doi.org/10.5281/zenodo.2656626)
* Paper on NK cells and multiple sclerosis: [bioRxiv](https://doi.org/10.1101/865477), [journal](https://doi.org/10.3389/fimmu.2020.00714)
* Paper on NK cells and HIV: [bioRxiv](https://doi.org/10.1101/764217), [journal](https://doi.org/10.1097/QAD.0000000000002488)
* Paper on NK cells and pregnancy: [bioRxiv](https://doi.org/10.1101/349084), [journal](https://doi.org/10.3389/fimmu.2019.02469)
* Paper on NK cells and influenza: [bioRxiv](https://doi.org/10.1101/148528), [journal](http://dx.doi.org/10.4049/jimmunol.1800161), [github](https://github.com/ChristofSeiler/nk_influenza)
* Latent class regression: [github](https://github.com/ChristofSeiler/Ascona_Talk)

## Regression Models for Functional Brain Connectivity

In this applied statistics project, we modeled brain connectivity for functional resting-state Magnetic Resonance Imaging (rfMRI) studies using two multivariate heteroscedasticity models. We applied our models to processed brain connectivity data from the Human Connectome Project (HCP) to compare short and conventional sleepers.

* Paper: [open access](https://doi.org/10.3389/fnins.2017.00696)
* Supplementary material: [Power Analysis](https://christofseiler.github.io/CovRegFC_HCP/Power.html), [Low-Dimensional Model Analysis](https://christofseiler.github.io/CovRegFC_HCP/Low_Dimensional.html), and [Full Model Analysis](https://christofseiler.github.io/CovRegFC_HCP/Full.html)
* R package: [github](https://github.com/ChristofSeiler/CovRegFC)
* Data analysis workflow: [github](https://github.com/ChristofSeiler/CovRegFC_HCP)

## Heterogeneous Data Integration for Neuroimaging

In collaboration with [Allan L. Reiss](https://med.stanford.edu/profiles/allan-reiss) and his [lab](http://cibsr.stanford.edu/) at Stanford School of Medicine, we studied interactions between brain imaging and cognitive data in girls with Turner syndrome. The procedure combines multi-table methods with permutation tests by constructing cluster size test statistics that incorporate spatial dependencies.

* Paper: [pdf](https://christofseiler.github.io/braincog/BrainCognitionArticle_Neuroinformatics.pdf), [open access](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6223630/)
* Supplementary material: [github](https://github.com/ChristofSeiler/braincog_manuscript)
* R package: [github](https://github.com/ChristofSeiler/braincog)
* Data analysis workflow: [Interactions](https://christofseiler.github.io/braincog/supplementary_materials/Interactions_2.html)

## Diagnostics of Hamiltonian Monte Carlo

In this mathematical statistics project, we estimated running times of Hamiltonian Monte Carlo in high dimensions using Riemannian geometry and coarse Ricci curvature. We proposed a new metric based on the generalization of curvature to Riemannian manifolds, namely sectional curvature. We derived asymptotic sectional curvature for the multivariate normal distribution and showed simulation results for the multivariate t distribution with varying degrees of freedom. Our results suggest sectional curvature as a quality control tool during Hamiltonian Monte Carlo simulations.

* Paper: [arXiv](http://arxiv.org/abs/1407.1114), [NIPS](http://papers.nips.cc/paper/5500-positive-curvature-and-hamiltonian-monte-carlo.pdf)
* Poster: [pdf](https://christofseiler.github.io/NIPS-Poster.pdf)
* R package: [github](https://github.com/ChristofSeiler/curvature), [vignette](https://christofseiler.github.io/vignettes/curvature.html)

## Bayesian Statistics in Computational Anatomy

My first three years as a postdoctoral fellow were funded by the Swiss National Science Foundation for a project on uncertainty quantification in computational anatomy. Most neuroimaging studies (and medical imaging studies in general) require registration of subjects to a template brain. The goal is to estimate non-linear deformations that map subjects to a template brain. Many algorithms are available, but few provide confidence or credible intervals. We addressed this issue in two projects.

First, we used modern Bayesian nonparametrics to find regions of interest in computed tomography images of the human spine:

* Paper: [pdf](https://hal.inria.fr/hal-00847185/document)
* Talk: [youtube (part 1)](https://www.youtube.com/watch?v=KZO-EaJ6Qrc), [youtube (part 2)](https://www.youtube.com/watch?v=B22UeW_wOpg)
* Software: [github](https://github.com/ChristofSeiler/BayesianNonparametrics.git)

Second, we built a Bayesian registration model and implemented the Hamiltonian Monte Carlo sampler to draw samples from its posterior distribution:

* Book chapter: [pdf](https://christofseiler.github.io/Preprint_Bayesian_CA.pdf), [DOI](https://www.elsevier.com/books/statistical-shape-and-deformation-analysis/zheng/978-0-12-810493-4)
* Software: [github](https://github.com/ChristofSeiler/BayesianImageRegistration)

## Medical Image Registration

During my PhD, we introduced a new type of structured medial image registration algorithm that can handle multiscale hierarchical anatomical structures. We applied our new method to mandible imaging data and showed how to design medical implants that fit a large population of people.

* Overview: [link](https://christofseiler.github.io/phd)
* Paper: [pdf](http://www.inria.fr/sophia/asclepios/Publications/Christof.Seiler/SeilerPolyaffineTransformationTreesMedIA2012.pdf)
* Software: [github](https://github.com/ChristofSeiler/PolyaffineTransformationTrees.git)

## Biomedical Engineering Applications

We applied our new registration method to a wide range of clinical applications. In collaboration with orthopaedic researchers, we compared the shape symmetry between left and right femur bones. In collaboration with orthopaedic implant designers, we constructed virtual mandible bones for better implant fitting and design. In collaboration with cardiac researchers, we modeled the dynamics of the human heart using ultrasound imaging. In collaboration with an orthopaedic surgeon in Argentina, we developed a bone allograft selection algorithm to pick the optimal bone from a femur bone bank for tumor replacement. In collaboration with mechanical engineers, we constructed statistical shape and appearance models to evaluate the mechanical properties of femur bones.

* Paper on implant design: [pdf](http://www.mauricioreyes.me/Publications/BouMiccai2012.pdf)
* Paper on dynamics of the human heart: [pdf](http://hal.inria.fr/hal-00840041/PDF/MICCAI_mcleod_2013.pdf)
* Paper on bone allograft selection: [pdf](http://www-sop.inria.fr/asclepios/Publications/Christof.Seiler/RitaccoSeilerCTB2012.pdf)
* Paper on mechanical properties of femur bones: [pdf](http://www.mauricioreyes.me/Publications/BonarettiMEP2014.pdf)

## Cell Shape Classifier

During my PhD, we classified stem cells during differentiation based on their shape from time-lapse video microscopy. Our algorithm was able to distinguish myogenic from osteogenic and adipogenic cells.

* Paper: [pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.303.6965&rep=rep1&type=pdf)
* Software: [github](https://github.com/ChristofSeiler/CellShapeClassifier)

## GPU Programming

For my MSc thesis, we implemented fast GPU code using shader processing to model soft tissue deformations with Markov random fields.

* Paper: [pdf](https://christofseiler.github.io/PaperHMRFDeformationGPU.pdf)
* Software: [github](https://github.com/ChristofSeiler/SoftTissueDeformations.git)
* Wikipedia entry citing our work: [link](https://en.wikipedia.org/wiki/Write-only_memory_(engineering)#cite_ref-7)
