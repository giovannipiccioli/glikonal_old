# Welcome to the *glikonal* repository!
This code computes the minimal altitude for an unpowered aircraft to return to an airfield.
It also computes the paths to follow for a safe re-entry.
The code is mainly built on top of the *pykonal* library available [here](https://github.com/malcolmw/pykonal).
This code implements the Fast Marching Method (FMM; Sethian *et al.*, 1996) for solving the eikonal equation in Cartesian or spherical coordinates in 2 or 3 dimensions.


## Installation

Download and unzip the [latest release](https://github.com/giovannipiccioli/glikonal/releases "Releases").
Then in the terminal execute
```bash
 cd path/to/glikonal
 pip install .
```

## Tutorials
The folder "gliding_distance" contains two jupyter notebooks that explain how to use the library.
### Artificial data
To better understand how the algorithm works one can start from artificial examples. In the notebook "examples_min_return_altitude", we look at the case of no terrain, a single mountain peak and a mountain range with two saddles.

This notebook goes though these various examples fo elevation profile, to show how glikonal computes the minimal altitude for re-entry and the re-entry paths.
Let us provide some pictures of this below.
For an elevation profile with a single peak, and glide ratio of 1, we can plot the minimal altitude contour lines (in white), on top of the elevation map (color indicates elevation).

### Real data



## Bugs
Please report bugs, feature requests, and questions through the [Issues](https://github.com/malcolmw/pykonal/issues "PyKonal Issues tracker") tracker.

## References
1. Sethian, J. A. (1996). A fast marching level set method for monotonically advancing fronts. *Proceedings of the National Academy of Sciences, 93*(4), 1591–1595. https://doi.org/10.1073/pnas.93.4.1591
2. White, M. C. A., Fang, H., Nakata, N., & Ben-Zion, Y. (2020). PyKonal: A Python Package for Solving the Eikonal Equation in Spherical and Cartesian Coordinates Using the Fast Marching Method. *Seismological Research Letters, 91*(4), 2378-2389. https://doi.org/10.1785/0220190318

