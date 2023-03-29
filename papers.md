---
layout: default
---

# Accepted Papers

This is the list of all accepted papers. You can find more information
about each submission by following either the *Forum* link or by visiting
our [OpenReview Workshop Website](https://openreview.net/group?id=ICLR.cc/2023/Workshop/Physics4ML). Please note that not all submissions are revised yet.

# Statistics

We received 66 submissions in total, of which we accepted 5 spotlights
and 52 poster presentations. All submissions received at least two
reviews and one meta-review.

Congratulations to all authors!


# Spotlights

<div style="text-align:center">
&#10086;
</div>

**Latent SDEs for Modelling Quasar Variability and Inferring Black Hole Properties** (Spotlight presentation)<br />
Joshua Fagin &bull; Ji Won Park &bull; Henry Best &bull; Matthew O'Dowd<br />
<abstract>Active galactic nuclei (AGN) are thought to be powered by the accretion of matter around supermassive black holes at the centers of galaxies. The variability of an AGN's brightness over time can provide valuable insights into the physical characteristics of its underlying black hole. The variability pattern is thought to closely follow a damped random walk, described by a stochastic differential equation (SDE). Upcoming wide-field telescopes are expected to observe 100 million AGN in multiple bandpass filters. Latent SDEs are well suited for modeling the AGN time series, as they explicitly model the underlying dynamics. We modify latent SDEs to jointly reconstruct the unobserved portions of multivariate AGN light curves as well as infer their physical properties, such as the black hole mass.  We train our model on a realistic physics-based simulation of ten-year AGN light curves, and we demonstrate its ability to fit AGN light curves even in the presence of long seasonal gaps and irregular sampling across different bands. Our method is general and applicable to a wide range of time series, and has the potential to provide a deeper understanding of the physical properties of black holes in AGN.</abstract>

[PDF](https://openreview.net/pdf?id=x2NOLHCPhg) &bull;
[Forum](https://openreview.net/forum?id=x2NOLHCPhg)


<div style="text-align:center">
&#10086;
</div>

**Learning protein family manifolds with smoothed energy-based models** (Spotlight presentation)<br />
Nathan C. Frey &bull; Dan Berenberg &bull; Joseph Kleinhenz &bull; Isidro Hotzel &bull; Julien Lafrance-Vanasse &bull; Ryan Lewis Kelly &bull; Yan Wu &bull; Arvind Rajpal &bull; Stephen Ra &bull; Richard Bonneau &bull; Kyunghyun Cho &bull; Andreas Loukas &bull; Vladimir Gligorijevic &bull; Saeed Saremi<br />
<abstract>We resolve difficulties in training and sampling from discrete energy-based models (EBMs) by learning a smoothed energy landscape, sampling the smoothed data manifold with Langevin Markov chain Monte Carlo, and projecting back to the true data manifold with one-step denoising. Our formalism combines the attractive properties of EBMs and improved sample quality of score-based models, while simplifying training and sampling by requiring only a single noise scale. We demonstrate the robustness of our approach on generative modeling of antibody proteins.</abstract>

[PDF](https://openreview.net/pdf?id=IilnB8jfoP9) &bull;
[Forum](https://openreview.net/forum?id=IilnB8jfoP9)

<div style="text-align:center">
&#10086;
</div>

**Multi-Scale Message Passing Neural PDE Solvers** (Spotlight presentation)<br />
Léonard Equer &bull; T. Konstantin Rusch &bull; Siddhartha Mishra<br />
<abstract>We propose a novel multi-scale message passing neural network algorithm for learning the solutions of time-dependent PDEs. Our algorithm possesses both temporal and spatial multi-scale resolution features by incorporating multi-scale sequence models and graph gating modules in the encoder and processor, respectively. Benchmark numerical experiments are presented to demonstrate that the proposed algorithm outperforms baselines, particularly on a PDE with a range of spatial and temporal scales.</abstract>

[PDF](https://openreview.net/pdf?id=jhH01LKEvB) &bull;
[Forum](https://openreview.net/forum?id=jhH01LKEvB)

<div style="text-align:center">
&#10086;
</div>

**Neural Networks Learn Representation Theory: Reverse Engineering how Networks Perform Group Operations** (Spotlight presentation)<br />
Bilal Chughtai &bull; Lawrence Chan &bull; Neel Nanda<br />
<abstract>We present a novel algorithm by which neural networks may implement composition for any finite group via mathematical representation theory, through learning several irreducible representations of the group and converting group composition to matrix multiplication. We show small networks consistently learn this algorithm when trained on composition of group elements by reverse engineering model logits and weights, and confirm our understanding using ablations. We use this as an algorithmic test bed for the hypothesis of universality in mechanistic interpretability -- that different models learn similar features and circuits when trained on similar tasks. By studying networks trained on various groups and architectures, we find mixed evidence for universality: using our algorithm, we can completely characterize the family of circuits and features that networks learn on this task, but for a given network the precise circuits learned -- as well as the order they develop -- are arbitrary.</abstract>

[PDF](https://openreview.net/pdf?id=j4_YHiTAN63) &bull;
[Forum](https://openreview.net/forum?id=j4_YHiTAN63)

<div style="text-align:center">
&#10086;
</div>

**Semi-Equivariant Conditional Normalizing Flows** (Spotlight presentation)<br />
Eyal Rozenberg &bull; Daniel Freedman<br />
<abstract>We study the problem of learning conditional distributions of the form 
, where  and 
 are two 3D graphs, using continuous normalizing flows.  We derive a semi-equivariance condition on the flow which ensures that conditional invariance to rigid motions holds.  We demonstrate the effectiveness of the technique in the molecular setting of receptor-aware ligand generation.
</abstract>

[PDF](https://openreview.net/pdf?id=jzfb_0Odl6l) &bull;
[Forum](https://openreview.net/forum?id=jzfb_0Odl6l)

# Accepted Posters
