# Python cookiecutter template
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a Python project.

* GitHub repo: https://github.com/audreyfeldroy/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: MIT License

## Features
* Build and dependency management tool with [poetry](https://python-poetry.org/)
* Makefile for automating tasks
* Dockerfile
* Testing setup with pytest
  * Unit and integration tests (check [testing pyramid](https://martinfowler.com/bliki/TestPyramid.html))
* Code checks
  * Type checks with mypy
  * Lint checks with pylint 
  * Auto formatting with black
* Command line interface using Click, Argparse (optional)

## Quickstart
Install the latest Cookiecutter if you haven't installed it yet:

https://cookiecutter.readthedocs.io/en/latest/installation.html

Generate a Python package project:
```bash
cookiecutter https://github.com/meandor/python-poetry-cookiecutter.git
```
