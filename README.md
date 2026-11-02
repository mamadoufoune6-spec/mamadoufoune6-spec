# Mamadou Foune Barry

**BSc Mathematics with Statistics · Lancaster University**<br>
Predicted First-Class Honours · Expected graduation July 2027

I'm interested in how autonomous systems reason and act under uncertainty, particularly **Bayesian inference, belief-space planning, active sensing and dual control**. My projects also explore inverse problems and the reliability of scientific machine learning.

## Research projects

### Belief-Space Planning for Autonomous Source Localisation

Developing a simulation framework in which a robot searches for a hidden radio source using noisy received signal-strength (RSSI) measurements.

- Bayesian belief updates over candidate source locations.
- Greedy MAP-based pursuit and information-seeking control.
- Evaluating search behaviour using trajectories, posterior uncertainty and success under explicit simulation assumptions.
- **Current direction:** evaluate experimental belief-space and dual-control variants alongside these baselines. General performance advantages are not established.

**Status:** Active simulation research. Public code release under review.

### Inpainting PHANGS–ALMA Spectral Cubes

Studied self-supervised reconstruction of masked three-dimensional CO(2–1) spectral cubes using a shared masked-autoencoder framework with linear, Conv3D and neural cellular automata reconstruction heads.

The evaluation considers random, frequency-varying and structured masking, with attention to **scientific fidelity** (including flux recovery) as well as conventional reconstruction metrics. A central question is whether better image-level scores preserve the scientific quantities researchers care about.

**Status:** Research manuscript and code under review for public release.

### Scientific Functional Ambiguity in Inverse Problems

A preliminary mathematical investigation of what can be inferred about a scientific quantity when multiple states agree with the same observations.

For a forward operator $A$, two states can satisfy $Ax_1 = Ax_2$ while yielding different values of a scientific functional $F$. My preliminary report examines exact finite perturbations, nullspace orientation, positivity constraints and linear-fractional functionals.

**Status:** Preliminary technical report (2026); public PDF release pending. This is not presented as peer-reviewed work.

## Selected PyTorch projects

| Project | Focus |
| --- | --- |
| [CIFAR-10 CNN](https://github.com/mamadoufoune6-spec/cifar10-cnn-pytorch) | Image classification, training and validation, checkpoint selection and held-out testing |
| [KMNIST MLP](https://github.com/mamadoufoune6-spec/kmnist-mlp-pytorch) | Training and evaluation workflow, reproducible data splits and learning-curve analysis |

These were **learning implementations**, not claimed research contributions or optimised benchmarks. Each repository contains its own setup instructions, experiment results, limitations and notes on AI-assisted engineering changes.

## Tools and interests

**Programming and scientific computing:** Python, NumPy, SciPy, pandas, PyTorch, numerical modelling and data visualisation.<br>
**Methods used in projects:** Bayesian inference, numerical methods, constrained optimisation, inverse problems, self-supervised learning and 3D reconstruction.<br>
**Current research interests:** Autonomous search, stochastic control, belief-space planning, active perception and model-based reinforcement learning.

---

**Contact:** [Lancaster University email](mailto:F.barry@lancaster.ac.uk)
