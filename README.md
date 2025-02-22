# saspt

<img src="https://github.com/alecheckert/saspt/blob/main/doc/_static/logo.png" alt="alt text" width="300">

`saspt` is a tool for analyzing single particle tracking (SPT) experiments. It relies on *state arrays*, a class of variational Bayesian models that identifies
diffusing subpopulations in the presence of large measurement error.
It is particularly useful for complex samples with many subpopulations with distinct
dynamics.

See the [Documentation](https://saspt.readthedocs.io/en/latest/) for more info. 

See the `examples` directory for usage examples.

## Install

Method 1 (recommended): install from PyPI:
```
  pip install saspt
```

Method 2: install from source

```
  git clone https://github.com/alecheckert/saspt
  cd saspt
  pip install -e .
```
