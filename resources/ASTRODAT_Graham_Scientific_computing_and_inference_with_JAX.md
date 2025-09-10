## JAX for scientific computing and inference

__Speaker__: Matt Graham ([matt-graham](https://github.com/matt-graham))

__Abstract__: JAX is an open-source Python package for high-performance numerical computing.
It provides a familiar NumPy style interface but with the advantages of allowing computations to be dispatched to accelerator devices such as graphics and tensor processing units,
and supporting transformations to automatically differentiate, vectorize and just-in-time compile functions.
While extensively used in machine learning applications, JAX's design also makes it ideal for scientific computing tasks such as simulating numerical models and fitting them to data.
This interactive tutorial will introduce JAX's interface, its computation model and functional transforms,
and illustrate how it can be used in an example task of inferring the posterior distribution on the parameters of a numerical model given data. 
The tutorial will also demonstrate how the Array API can be used to write portable code which works across JAX, NumPy and other array backends.

- [Slides](matt-graham.github.io/slides/jax-sci-comp)
- [Repository with associated notebook and material](https://github.com/matt-graham/jax-sci-comp-demo)
