
# sanipy

Bring some sanity to R when working with Python via reticulate

## Description

A set of utilities and helpers that make using Python via `reiculate` a
bit saner.

See
<https://rud.is/b/2018/08/04/digging-into-mbox-details-a-tale-of-tm-reticulate/>
for some functionality or look at the examples in the manual pages.

## What’s Inside The Tin

The following functions are implemented:

Stucture inspection helpers:

  - `pystr`: Compactly Display the Structure of a Python object
  - `pynames`: (All) The Names of a Python Object

Strng helpers:

  - `get_chr`: Retrieve a value from a Python ‘dict’ as a character
  - `utf8_decode`: Decode a Python structure and retrieve a UTF-8
    encoded value from it

Documentation helpers:

  - `py_doc`: Use built-in ‘pydoc’ to get the Python HTML manual page
    for a given object
  - `readthedocs`: Use “Read the Docs” to get help on a Python
    module/object

General Utility:

  - `%|0|%`: Default value for an object length being 0

## Installation

``` r
devtools::install_git("https://gitlab.com/hrbrmstr/sanipy.git")
# or
devtools::install_github("hrbrmstr/sanipy")
```

## Usage

``` r
library(sanipy)

# current verison
packageVersion("sanipy")
```

    ## [1] '0.1.0'
