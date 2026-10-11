# Mathematical Foundations of Diffusion-Based Generative Modeling

This repository contains my Master’s thesis in Applied Mathematics at ETH Zurich and the code used to produce its figures.

The thesis studies the mathematical foundations of diffusion-based generative models, including their connections to Schrödinger bridges, with applications to financial time series and protein backbone generation. 

## Contents

- **Thesis:** the full manuscript, including the mathematical analysis and applications.
- **Notebook:** the code used to generate the figures presented in the thesis.

## Main contributions


- **Extension of an invariance result, section 4.2.4.** Identify a gap in the application of a Lie-group invariance proposition to centred protein configurations in the original paper "SE(3) diffusion model with application to protein backbone generation" (ICML 2023). Formulate and prove an extension to isometric group actions on Riemannian manifolds, establishing preservation of distributional invariance and score equivariance under explicit assumptions.

- **Critical analysis of financial time-series generation and alternative proof, sections 4.1.2 and 4.1.3.** Provide an alternative proof of one of the main results of the original paper "Generative modeling for time series via Schrödinger bridge". Examine the statistical assumptions behind Schrödinger-bridge methods, particularly dependence introduced by overlapping windows, bandwidth sensitivity and evaluation metrics. Discuss potential memorization effects as hypotheses requiring further empirical validation.
