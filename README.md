# Evolutionary Computation

### Evolutionary Strategies

## Key Features
1. **Representation**: Solutions in ES are vectors of real numbers, which can denote system parameters, design variables, etc.

2. **Mutation and Recombination**:
    - **Mutation**: The core search operator in ES. It introduces random variation by perturbing real-valued vectors, often using a Gaussian distribution.
    - **Recombination**: Averages two parent solutions or mixes components from multiple parents.

3. **Self-Adaptation**: Strategy parameters, such as mutation step size, evolve with the solution. This enables an individual solution to refine its mutation behavior over its lifespan.

## ES Variants
- **(µ, λ) Selection**: µ parents produce λ offspring. Only the offspring compete for the next generation.
- **(µ+λ) Selection**: Both parents and offspring vie for spots in the next generation.



