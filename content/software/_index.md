## Stochastic Simulation

### [BioSimulator.jl](https://github.com/alanderos91/BioSimulator.jl)

Stochastic simulation of Markov chains representing discrete dynamical systems using the [Julia language](https://julialang.org/).
It provides an [easy-to-use model building system](https://github.com/alanderos91/LangeSymposium-BioSimulator/blob/master/01-Modeling-Well-Mixed-Systems.ipynb) and implements commonly used [Gillespie-like algorithms](https://en.wikipedia.org/wiki/Gillespie_algorithm) as well as [$\tau$-leaping methods](https://en.wikipedia.org/wiki/Tau-leaping).

In collaboration with Tim Stutz, I also implemented support for simulating stochastic processes with a spatial component using interacting particle systems.

#### Related

- [BioSimualtorPetriNets.jl](https://github.com/alanderos91/BioSimulatorPetriNets.jl): Draw [petri nets](https://en.wikipedia.org/wiki/Petri_net) from well-mixed models in BioSimulator.jl.

## Optimization

### [ProximalDistanceAlgorithms.jl](https://github.com/alanderos91/ProximalDistanceAlgorithms.jl)

Implements proximal distance algorithms for

- metric nearness problems,
- convex regression,
- sparse convex clustering,
- image denoising, and
- improving a matrix's condition number

as examples that illustrate the flexibility of the proximal distance principle.

## Classification

### [SparseMVDA.jl](https://github.com/alanderos91/SparseMVDA)

Implements algorithms for fitting sparse classifiers based on vertex discriminant analysis.
Fitting a single classifier to predict multiple classes improves prediction, lends interpretability to selected features, and reduces computational burden.

### [SparseSVM.jl](https://github.com/alanderos91/SparseSVM.jl)

Implements algorithms for fitting sparse $L_{2}$ support vector machines (SVM) using distance majorization.
By constructing a quadratic surrogate for the original loss, we can quickly fit a SVM with no more than $k$ active features.
Model stability can be assessed with repeated cross validation.
Both binary and multiclass problems are supported.
