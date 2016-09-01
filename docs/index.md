[![Build Status](https://travis-ci.org/qiqi/fds.svg?branch=master)](https://travis-ci.org/qiqi/fds.svg?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/qiqi/fds/badge.svg?branch=master)](https://coveralls.io/github/qiqi/fds?branch=master)
[![Dependency Status](https://dependencyci.com/github/qiqi/fds/badge)](https://dependencyci.com/github/qiqi/fds)
[![Documentation Status](https://readthedocs.org/projects/fds/badge/?version=latest)](http://fds.readthedocs.io/en/latest/?badge=latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

# What's it for

fds is a research tool for computational simulations that exhibis
chaotic dynamics. It computes sensitivity derivatives of time averaged
quantities, a.k.a. statistics, with respect simulation parameters.

For an introduction of chaotic dynamics, I highly recommend [Strogatz's
excellent book](https://www.amazon.com/gp/product/0813349109). For a
statistical view of chaotic dynamical systems, please refer to
[Berlinger's article](http://www.uvm.edu/~pdodds/files/papers/others/1992/berliner1992a.pdf).
Algorithm used in this software is described in [the upcoming AIAA
paper](https://dl.dropbox.com/s/2e9jxjmwh375i01/fds.pdf)

# Download and use

The best way to download fds is using pip. Pip is likely included in
your Python installation. If not, see [instruction
here](https://pip.pypa.io/en/stable/installing/). To install fds
using pip, simply type

```
sudo pip install fds
```

# Tutorials

-  [First example -- Van der Pol oscillator in Python](tutorials/vanderpol.md)
-  [Lorenz attractor in C](tutorials/lorenz_c.md)
-  [Lorenz 96 in MPI and C](tutorials/lorenz96_mpi.md)

# Guides

-  [Chaos and statistical convergence](guides/statistics.md)
-  [Lyapunov exponents and time
   segmentation](guides/lyapunov.md)
-  [Save and restart](guides/save_restart.md)

# Reference

-  [The least squares shadowing algorithm](ref/lss_algorithm.md)
-  [Function reference](ref/function_ref.md)
-  [License](https://www.gnu.org/licenses/gpl-3.0.en.html)