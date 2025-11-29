---
title: "Machine Learning Generalised DFT+<em>U</em> Projectors in a Numerical Atom-Centred Orbital Framework"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1

excerpt: "We present machine learning-based workflows using symbolic regression and support vector machines to simulataneously optimise Hubbard <em>U</em> values and projectors, enabling accurate and efficient simulations of defects and polarons in transition metal and rare-earth oxides. [Click to read the full abstract]"

date: 2025-10-30
venue: 'Digital Discovery'
slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
## Abstract

Accurate electronic structure simulations of strongly correlated metal oxides are crucial for the atomic level understanding of heterogeneous catalysts, batteries and photovoltaics, but remain challenging to perform in a computationally tractable manner. Hubbard corrected density functional theory (DFT+<em>U</em>) in a numerical atom-centred orbital framework has been shown to address this challenge but is susceptible to numerical instability when simulating common transition metal oxides (TMOs), <em>e.g.</em>, TiO<sub>2</sub> and rare-earth metal oxides (REOs), <em>e.g.</em>, CeO<sub>2</sub>, necessitating the development of advanced DFT+<em>U</em> parameterisation strategies. In this work, the numerical instabilities of DFT+<em>U</em> are traced to the default atomic Hubbard projector, which we refine for Ti 3<em>d</em> orbitals in TiO<sub>2</sub> using Bayesian optimisation, with a cost function and constraints defined using symbolic regression (SR) and support vector machines, respectively. The optimised Ti 3<em>d</em> Hubbard projector enables the numerically stable simulation of electron polarons at intrinsic and extrinsic defects in both anatase and rutile TiO<sub>2</sub>, with comparable accuracy to hybrid-DFT at several orders of magnitude lower computational cost. We extend the method by defining a general first-principles approach for optimising Hubbard projectors, based on reproducing orbital occupancies calculated using hybrid-DFT. Using a hierarchical SR-defined cost function that depends on DFT-predicted orbital occupancies, basis set parameters and atomic material descriptors, a generalised workflow for the one-shot computation of Hubbard <em>U</em> values and projectors is presented. The method transferability is shown for 10 prototypical TMOs and REOs, with demonstrable accuracy for unseen materials that extends to complex battery cathode materials like LiCo<sub>1-x</sub>Mg<sub>x</sub>O<sub>2-x</sub>. The work highlights the integration of advanced machine learning algorithms to develop cost-effective and transferable workflows for DFT+<em>U</em> parameterisation, enabling more accurate and efficient simulations of strongly correlated metal oxides.

