---
title: "Compositional Generative Multiphysics and Multi-component Simulation"
collection: publications
category: manuscripts
permalink: /publication/2024-12-05-multisimdiff
excerpt: 'Multiphysics simulation, which models the interactions between multiple physical processes, and multi-component simulation of complex structures are critical in fields like nuclear and aerospace engineering. Previous studies often rely on numerical solvers or machine learning-based surrogate models to solve or accelerate these simulations. However, multiphysics simulations typically require integrating multiple specialized solvers-each responsible for evolving a specific physical process-into a coupled program, which introduces significant development challenges. Furthermore, no universal algorithm exists for multi-component simulations, which adds to the complexity. Here we propose compositional Multiphysics and Multi-component Simulation with Diffusion models (MultiSimDiff) to overcome these challenges. During diffusion-based training, MultiSimDiff learns energy functions modeling the conditional probability of one physical process/component conditioned on other processes/components. In inference, MultiSimDiff generates coupled multiphysics solutions and multi-component structures by sampling from the joint probability distribution, achieved by composing the learned energy functions in a structured way. We test our method in three tasks. In the reaction-diffusion and nuclear thermal coupling problems, MultiSimDiff successfully predicts the coupling solution using decoupled data, while the surrogate model fails in the more complex second problem. For the thermal and mechanical analysis of the prismatic fuel element, MultiSimDiff trained for single component prediction accurately predicts a larger structure with 64 components, reducing the relative error by 40.3% compared to the surrogate model.'
date: 2024-12-05
venue: 'arXiv preprint'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://taozhan18.github.io/files/multisimdiff.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
