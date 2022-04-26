# Linting - What is all the fluff about?

## Pre-requisites

Familiarity with Python and virtual environments (e.g. Miniconda) and using Git/GitHub/GitHub Actions.

### Create a dedicated virtual environment


``` bash
# Using Conda
conda create linting

# Using venv
mkdir -p ~/work/linting && cd ~/work/linting
virtualenv linting
source linting/bin/activate

# Using virtualenvwrapper (a useful abstraction of virtualenv)
pip install virtualenvwrapper
export WORKON_HOME=~/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
mkvirtualenv linting
workon linting
```
* [Miniconda Installation](https://docs.conda.io/en/latest/miniconda.html)
* [virtualenv documentation](https://virtualenv.pypa.io/en/latest/)
* [virtualenvwrapper | installation](http://virtualenvwrapper.readthedocs.org/en/latest/install.html)

### Clone the repository

A set of sample files are provided as part of the repository
[ns-rse/fluff-removal](https://github.com/ns-rse/fluff-removal/), clone the repository to obtain these.

``` bash
mkdir -p ~/work/rsecon2022 && cd ~/work/rsecond2022
git clone git@github.com:ns-rse/fluff-removal.git
cd fluff-removal
```

### Install the required packges

For convenience all the required packages are listed in the `requirements.txt` file, you can install these with
[pip](https://pip.pypa.io/en/stable/) using

``` bash
pip install -r requirements.txt
```

## What is Linting?


## Why Lint?

## How to Lint Python Code

There are various packages and tools for linting your Python code.


### Command Line

### IDE integration

### Continuous Integration

## Other Tools

## Links

### Python

* [Flake8](https://flake8.pycqa.org/en/latest/) - Your Tool For Style Guide Enforcement
* [Black](https://github.com/psf/black) - The Uncompromising Code Formatter
* [Yapf](https://pylint.pycqa.org/en/latest/) - Yet Another Python Formatter.
* [Pylint](https://pylint.pycqa.org/en/latest/) - Check for errors, look for code smells and enforce coding standards.
* [Pylint : Overview of all Pylint messages](https://pylint.pycqa.org/en/latest/messages/messages_list.html)

### R

### C++

### IDE Configuration

* [Linting Python in Visual Studio Code](https://code.visualstudio.com/docs/python/linting)
