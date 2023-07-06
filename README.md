![](https://img.shields.io/github/issues/malcolmw/pykonal)
![](https://img.shields.io/github/forks/malcolmw/pykonal)
![](https://img.shields.io/github/stars/malcolmw/pykonal)
![](https://img.shields.io/github/license/malcolmw/pykonal)
# Welcome to the *glikonal* repository!
This code computes the minimal altitude for an unpowered aircraft to return to an airport.
The code is mainly built on top of the *pykonal* library available [here](https://github.com/malcolmw/pykonal).
This code implements the Fast Marching Method (FMM; Sethian *et al.*, 1996) for solving the eikonal equation in Cartesian or spherical coordinates in 2 or 3 dimensions.


## Installation

### From source code
Download and unzip the [latest release](https://github.com/giovannipiccioli/glikonal/releases "Releases").
```bash
sh$> cd path/to/pykonal
sh$> pip install .
```
## Bugs
Please report bugs, feature requests, and questions through the [Issues](https://github.com/malcolmw/pykonal/issues "PyKonal Issues tracker") tracker.

## References
1. Sethian, J. A. (1996). A fast marching level set method for monotonically advancing fronts. *Proceedings of the National Academy of Sciences, 93*(4), 1591–1595. https://doi.org/10.1073/pnas.93.4.1591
2. White, M. C. A., Fang, H., Nakata, N., & Ben-Zion, Y. (2020). PyKonal: A Python Package for Solving the Eikonal Equation in Spherical and Cartesian Coordinates Using the Fast Marching Method. *Seismological Research Letters, 91*(4), 2378-2389. https://doi.org/10.1785/0220190318

