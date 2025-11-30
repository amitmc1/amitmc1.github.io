---
title: "Mixture-of-Experts Transformers for Faithfully Deorbitalized Meta-GGA Density Functionals"
collection: publications
category: pre-prints
share: false
permalink: /publication/2025-10-30-metagga-transformers

excerpt: "We adopt a physics-informed deep learning approach to reparameterise popular semi-local meta-GGA density functionals into non-local deorbitalized surrogates that more faithfully mimic their orbital-dependent parent functionals. This is achieved using a Mixture-of-Experts transformers architecture that uses multi-head self-attention and automatic differentiation to accurately predict exchange energy densities and partial derivatives across a diverse set of molecules and materials. The architecture is designed to replace the expensive feature-based non-locality from the orbital-dependent kinetic energy density with architectural non-locality implemented using attention."

date: 2025-10-30
venue: 'ChemRxiv (DOI: 10.26434/chemrxiv-2025-mrgzj-v2)'
citation: 'A. Chaudhari and A. J. Logsdail, Mixture-of-Experts Transformers for Faithfully Deorbitalized Meta-GGA Density Functionals, <em>ChemRxiv</em>, 2025, DOI: 10.26434/chemrxiv-2025-mrgzj-v2'
---

<p align="center">
  <img src="{{ site.baseurl }}/images/MoE_abstract.png" alt="Graphical Abstract" style="max-width: 600px; width: 100%; border-radius: 0px;">
</p>

## Abstract

Meta-GGA density functional theory (DFT) is an important method in <em>ab initio</em> materials modelling; however, its computational cost limits applicability for generating large datasets or simulating extended length and time scales, as necessary for modern materials discovery. Deorbitalization is a promising strategy to accelerate meta-GGA DFT by removing the explicit orbital dependence of the exchange-correlation energy and potential using an approximation for the non-local kinetic energy density. Currently, achieving both accuracy and stability in practical deorbitalized simulations remains challenging, as many popular exchange-correlation density functionals are rigidly structured and inherently resistant to deorbitalization. These challenges motivate the need to understand the adaptability of traditional density functionals and to develop more advanced strategies for their design. Guided by this understanding, we adopt a physics-informed deep learning approach to reparameterize popular semi-local meta-GGA density functionals into non-local deorbitalized surrogates that more faithfully mimic their orbital-dependent parent functionals. Our approach is investigated for the deorbitalization of the MS2 exchange density functional of Sun <em>et al.</em> (DOI: 10.1063/1.4789414) using a transformer encoder that leverages multi-head self-attention and automatic differentiation to accurately predict exchange energy densities and partial derivatives across real-space integration grids. The outcome is a deep learning-based procedure for deorbitalizing meta-GGA density functionals that generalizes across diverse chemical bonding environments in both molecules and materials using a sparse mixture-of-experts model. The work shows the potential of advanced deep learning architectures towards constructing accurate surrogate models of expensive electronic structure methods, whilst outlining a path towards robust deorbitalized simulations of molecules and solids.
