A tutorial on Amortised Approximate Ratio Estimation (AALR) for the COMPASS Seminar Series at the University of Bristol.

## Table of contents

- [Requirements](#requirements)
- [Slides](#slides)
- [Setup](#setup)
- [Notebooks](#notebooks)

## Requirements

> **Required**. The project assumes you have a working Anaconda installation.

Anaconda can be installed by executing the following commands in your terminal.
Please note the commands below are intended for a Linux installation.
For other operating systems please check the Anaconda [website](https://www.anaconda.com/products/individual).

```console
you@localhost:~ $ wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
you@localhost:~ $ sh Miniconda3-latest-Linux-x86_64.sh
```

After your Anaconda installation has been installed, we can create a `compass-tutorial` environment with the required packages:

```console
you@localhost:~ $ conda create -n compass-tutorial python=3.8
you@localhost:~ $ conda activate compass-tutorial
you@localhost:~ $ pip install -r requirements.txt
```

## Slides

The slides can be viewed by starting an HTTP server to serve the slides at [localhost:8000](http://localhost:8000).
```console
you@localhost:~ $ python -m http.server --directory slides 8000
```
Alternatively, you can also view the slides [online](https://joerihermans.com/talks/talk-compass-tutorial).

#### Credits

Template adapted from [Gilles Louppe](https://github.com/glouppe/talk-template).

## Notebooks

The following tutorial notebooks are available:

| Name | Short description |
| --- | --- |
| [tutorial.ipynb](tutorial/tutorial.ipynb) | Introduction notebook |
