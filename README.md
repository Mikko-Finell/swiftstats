# SwiftStats

All credit to the original authors: https://github.com/r0fls/swiftstats

SwiftStats is open-source with automated testing and automatically-generated documentation.  If you'd like to help out we'd welcome contributions.

## Features
### Distributions
Currently the following distributions are included: 
- Normal
- Log-normal
- Bernoulli 
- Laplace 
- Poisson
- Uniform
- Geometric
- Exponential
- Binomial

And each distribution has these methods:
- pmf or pdf
- cdf
- quantile
- random (takes an optional int and returns an array of that length, or otherwise a single value) 

### Common Functions
- median
- mean
- variance
- standard deviation
- erf<sup>-1</sup> (implemented as `erfinv`, whereas `erf` is implemented as part of `Foundation`)
- least squares regression; lsr ([[`Double`]]) -> [`Double`, `Double`]
- kernel density estimation (KDE) using a Gaussian kernel and automatic bandwidth selection via Silverman's rule-of-thumb

## License
All code that I created in this repository (which is everything that was not generated by Xcode from a template, including the main source and the Unit Tests) is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/), which means that it is part of the public domain and you can do anything with it, without asking permission. In places where Xcode automatically attributed copyright to Raphael Deem or Matthew Walker, this overrides that.
