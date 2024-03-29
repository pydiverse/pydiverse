# pydiverse

[![CI](https://github.com/pydiverse/pydiverse/actions/workflows/ci.yml/badge.svg)](https://github.com/pydiverse/pydiverse/actions/workflows/ci.yml)

A collection of nicely interoperable libraries for data pipeline orchestration allowing for both SQL target and in-memory operation.

## Installation

You can install the package in development mode using:

```bash
git clone https://github.com/pydiverse/pydiverse.git
cd pydiverse

# create and activate a fresh environment named pydiverse
# see environment.yml for details
mamba env create
conda activate pydiverse

pre-commit install
pip install --no-build-isolation -e .
```
