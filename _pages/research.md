---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
  - /research.html
---

My research investigates how problem structure and computational choices shape what we learn from data. I use geometric and probabilistic tools to understand the dynamics of learning algorithms, the structure they exploit or produce, and the statistical conclusions their outputs support. My goal is to turn this understanding into principles for efficient learning and reliable inference.

A guiding idea is that **computational choices are part of the statistical method—not merely implementation details.** My current research is organized around three connected themes.

[Optimization dynamics](#optimization-dynamics) · [Structure and geometry](#structure-and-geometry) · [Inference beyond prediction](#inference-beyond-prediction)

<a id="optimization-dynamics"></a>

## Optimization Dynamics and Learning

**Central question:** *How do algorithmic choices determine the learning trajectory, the solution reached, and the statistical performance achievable with limited computation?*

I study learning algorithms as dynamical processes, asking not only whether they converge, but also what they learn along the way and which solutions they select. My interests include how step size, normalization, stochasticity, and parameterization shape these dynamics, and how the resulting behavior affects accuracy and computational efficiency. This perspective treats the optimizer as part of the learning procedure, rather than merely a means of minimizing an objective.

**Current directions.** A current focus is understanding large-step and oscillatory training dynamics, including behavior near the edge of stability. I am exploring descriptions that capture behavior across multiple iterations, with the aim of separating slow evolution from rapid oscillations and understanding how discrete optimization differs from continuous-time gradient flow. More broadly, I seek to connect algorithm-dependent dynamics to solution selection, statistical performance, and computational cost.

**Representative work**

- [Scaling laws of signSGD in linear regression: When does it outperform SGD?](https://proceedings.iclr.cc/paper_files/paper/2026/hash/6dd226b5bbbe3f243e99d19238ebeae8-Abstract-Conference.html) — ICLR, 2026.
- [Efficient low-dimensional compression of overparameterized models](https://proceedings.mlr.press/v238/min-kwon24a.html) — AISTATS, 2024.

<a id="structure-and-geometry"></a>

## Structure and Geometry in Statistical Learning

**Central question:** *What structure makes a learning problem tractable and statistically useful—and how should that structure be represented, imposed, or recovered?*

I study how the geometry of statistical models and optimization objectives shapes the structure of their solutions and what can be learned and computed. Examples include latent-variable models, nonconvex loss landscapes, low-dimensional representations, structured covariances, and convex relaxations. I am interested both in exploiting useful structure and in understanding when simplifying assumptions lose essential information. This includes asking which structures admit efficient representations, how closely simpler models approximate richer ones, and what limitations accompany those approximations.

**Current directions.** An emerging direction examines how the interaction between loss geometry and regularization determines the structure of learned solutions. Rather than viewing a regularizer in isolation, I aim to understand how the loss, the penalty, and the data together shape which structures are favored, and how that structure affects statistical and computational performance.

**Representative work**

- [Local minima structures in Gaussian mixture models](https://ieeexplore.ieee.org/abstract/document/10463706) — IEEE Transactions on Information Theory, 2024.
- [On approximations of the PSD cone by a polynomial number of smaller-sized PSD cones](https://link.springer.com/article/10.1007/s10107-022-01795-7) — Mathematical Programming, 2023.
- [Nearest neighbors for matrix estimation interpreted as blind regression for latent variable model](https://ieeexplore.ieee.org/abstract/document/8886428) — IEEE Transactions on Information Theory, 2020.

<a id="inference-beyond-prediction"></a>

## Inference Beyond Prediction

**Central question:** *When can flexible fitting support estimation of a scientifically meaningful quantity and valid uncertainty quantification—not merely accurate prediction?*

I develop theory for estimation and inference with high-dimensional and overparameterized models. A central focus is regression adjustment in randomized experiments: how covariate geometry and the fitting procedure affect bias, precision, and uncertainty quantification. More broadly, I investigate which aspects of a fitted model remain informative for a target of interest, and what additional assumptions or corrections are needed for valid inference. The goal is not simply to use a more flexible predictor, but to understand when and how doing so improves inference.

**Current directions.** My current work aims to connect finite-sample analyses of regression adjustment to implementable procedures with reliable uncertainty quantification. A developing direction asks how these questions change when the features themselves are learned from data. Throughout, I distinguish properties of the fitted model from the assumptions on the experimental design or data-generating process that justify statistical conclusions.

**Representative work**

- [Benign overfitting beyond prediction: The ordinary least squares interpolator](https://doi.org/10.1093/biomet/asag039) — Biometrika, 2026.
- [Design-based finite-sample analysis for regression adjustment](https://proceedings.mlr.press/v300/song26a.html) — AISTATS, 2026.
- [Neumann-series corrections for regression adjustment in randomized experiments](https://arxiv.org/abs/2511.08539) — Preprint.

## How the Themes Connect

These themes approach a common set of questions from complementary directions. **Structure and geometry** describe what a model can represent and which solutions a formulation favors. **Optimization dynamics** explain how a computational process moves through that space and which solutions it reaches. **Statistical inference** asks what can be concluded about a target from the resulting procedure, under an explicit data-generating model or experimental design. Together, these perspectives guide my efforts to understand not only how learning algorithms work, but also when their outputs are useful for the questions we want to answer.

A complete list of papers is available on my [publications page]({{ '/publications/' | relative_url }}).
