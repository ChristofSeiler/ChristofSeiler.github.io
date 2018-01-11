---
layout: page
title: Research Projects
---

## Biomedical Data Analysis

### Natural Killer Cells

In collaboration with the with [Catherine Blish](https://med.stanford.edu/profiles/catherine-blish) and her [lab](https://sites.stanford.edu/blishlab/) at Stanford School of Medicine, I am investigating how NK cells can be harnessed for therapeutic purposes. I develop and consult for several projects using RNA-seq, microarrays, and CyTOF data.

* Paper on statistical methods and workflow: in preparation
* Paper on NK cells and influenza: [bioRxiv](https://doi.org/10.1101/148528)
* R package: in preparation

### Functional Brain Connectivity

In this applied statistics project, I modeled brain connectivity for functional resting-state Magnetic Resonance Imaging (rfMRI) studies using two multivariate heteroscedasticity models. I applied our models to processed brain connectivity data from the Human Connectome Project (HCP) to compare short and conventional sleepers.

* Paper: [open access](https://doi.org/10.3389/fnins.2017.00696)
* Supplementary material: [Power Analysis](https://christofseiler.github.io/CovRegFC_HCP/Power.html), [Low-Dimensional Model Analysis](https://christofseiler.github.io/CovRegFC_HCP/Low_Dimensional.html), and [Full Model Analysis](https://christofseiler.github.io/CovRegFC_HCP/Full.html)
* R package: [github](https://github.com/ChristofSeiler/CovRegFC)
* Data analysis workflow: [github](https://github.com/ChristofSeiler/CovRegFC_HCP)

### Heterogeneous Data Integration

In collaboration with [Allan L. Reiss](https://med.stanford.edu/profiles/allan-reiss) and his [lab](http://cibsr.stanford.edu/) at Stanford School of Medicine, I studied interactions between brain imaging and cognitive data in girls with Turner syndrome. The procedure combines multi-table methods with permutation tests by constructing cluster size test statistics that incorporate spatial dependencies.

* Paper: [pdf](https://christofseiler.github.io/braincog/BrainCognitionArticle_Neuroinformatics.pdf)
* Supplementary material: [github](https://github.com/ChristofSeiler/braincog_manuscript)
* R package: [github](https://github.com/ChristofSeiler/braincog)
* Data analysis workflow: [Interactions](https://christofseiler.github.io/braincog/supplementary_materials/Interactions_2.html)

### Hamiltonian Monte Carlo

In this mathematical statistics project, I estimated running times of Hamiltonian Monte Carlo in high dimensions using Riemannian geometry and coarse Ricci curvature. I proposed a new metric based on the generalization of curvature to Riemannian manifolds, namely sectional curvature. I derived asymptotic sectional curvature for the multivariate normal distribution and showed simulation results for the multivariate t distribution with varying degrees of freedom. My results suggest sectional curvature as a quality control tool during Hamiltonian Monte Carlo simulations.

* Paper: [arXiv](http://arxiv.org/abs/1407.1114), [NIPS](http://papers.nips.cc/paper/5500-positive-curvature-and-hamiltonian-monte-carlo.pdf)
* Poster: [pdf](https://christofseiler.github.io/NIPS-Poster.pdf)
* R package: [github](https://github.com/ChristofSeiler/curvature), [vignette](https://christofseiler.github.io/vignettes/curvature.html)

## Biomedical Image Analysis

### Bayesian Statistics in Computational Anatomy

My first three years as a postdoctoral fellow were funded by the Swiss National Science Foundation for a project on uncertainty quantification in computational anatomy. Most neuroimaging studies (and medical imaging studies in general) require registration of subjects to a template brain. The goal is it estimate non-linear deformations that map subjects to a template brain. Many algorithms are available, but few provide confidence or credible intervals. I addressed this issue in two projects.

First, I used modern Bayesian nonparametrics to find regions of interest in computed tomography images of the human spine:

* Paper: [pdf](https://hal.inria.fr/hal-00847185/document)
* Talk: [youtube](https://www.youtube.com/watch?v=KZO-EaJ6Qrc)
* Software: [github](https://github.com/ChristofSeiler/BayesianNonparametrics.git)

Second, I built a Bayesian registration model and implemented the Hamiltonian Monte Carlo sampler to draw samples from its posterior distribution:

* Book chapter: [pdf](https://christofseiler.github.io/Preprint_Bayesian_CA.pdf), [DOI](https://www.elsevier.com/books/statistical-shape-and-deformation-analysis/zheng/978-0-12-810493-4)
* Software: [github](https://github.com/ChristofSeiler/BayesianImageRegistration)

### Medical Image Registration

During my PhD, I introduced a new type of structured medial image registration algorithm that can handle multiscale hierarchical anatomical structures. I applied my new method to mandible imaging data and showed how to design medical implants that fit a large population of people.

* Overview: [link](https://christofseiler.github.io/phd)
* Paper: [pdf](http://www.inria.fr/sophia/asclepios/Publications/Christof.Seiler/SeilerPolyaffineTransformationTreesMedIA2012.pdf)
* Software: [github](https://github.com/ChristofSeiler/PolyaffineTransformationTrees.git)

### Biomedical Engineering Applications

I applied my new registration method to a wide range of clinical applications. In collaboration with orthopaedic researchers, I compared the shape symmetry between left and right femur bones. In collaboration with orthopaedic implant designers, I constructed virtual mandible bones for better implant fitting and design. In collaboration with cardiac researchers, I modeled the dynamics of the human heart using ultrasound imaging. In collaboration with an orthopaedic surgeon in Argentina, I developed a bone allograft selection algorithm to pick the optimal bone from a femur bone bank for tumor replacement. In collaboration with mechanical engineers, I constructed statistical shape and appearance models to evaluate the mechanical properties of femur bones.

* Paper on implant design: [pdf](http://www.mauricioreyes.me/Publications/BouMiccai2012.pdf)
* Paper on dynamics of the human heart: [pdf](http://hal.inria.fr/hal-00840041/PDF/MICCAI_mcleod_2013.pdf)
* Paper on bone allograft selection: [pdf](http://www-sop.inria.fr/asclepios/Publications/Christof.Seiler/RitaccoSeilerCTB2012.pdf)
* Paper on mechanical properties of femur bones: [pdf](http://www.mauricioreyes.me/Publications/BonarettiMEP2014.pdf)

### Cell Shape Classifier

During my PhD, I classified stem cells during differentiation based on their shape from time-lapse video microscopy. My algorithm was able to distinguish myogenic from osteogenic and adipogenic cells.

* Paper: [pdf](https://pdfs.semanticscholar.org/a1f2/856b339318fd751d77a9cde70ffc07d9e863.pdf)
* Software: [github](https://github.com/ChristofSeiler/CellShapeClassifier)

### GPU Programming

For my MSc thesis, I implemented fast GPU code using shader processing to model soft tissue deformations with Markov random fields.

* Paper: [pdf](https://christofseiler.github.io/PaperHMRFDeformationGPU.pdf)
* Software: [github](https://github.com/ChristofSeiler/SoftTissueDeformations.git)
* Wikipedia entry citing our work: [link](https://en.wikipedia.org/wiki/Write-only_memory_(engineering)#cite_ref-7)
