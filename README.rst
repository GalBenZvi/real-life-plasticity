========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/papers-template/badge/?style=flat
    :target: https://papers-template.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/GalBenZvi/papers-template/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/GalBenZvi/papers-template/actions

.. |requires| image:: https://requires.io/github/GalBenZvi/papers-template/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/GalBenZvi/papers-template/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/GalBenZvi/papers-template/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/GalBenZvi/papers-template

.. |version| image:: https://img.shields.io/pypi/v/papers-template.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/papers-template

.. |wheel| image:: https://img.shields.io/pypi/wheel/papers-template.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/papers-template

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/papers-template.svg
    :alt: Supported versions
    :target: https://pypi.org/project/papers-template

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/papers-template.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/papers-template

.. |commits-since| image:: https://img.shields.io/github/commits-since/GalBenZvi/papers-template/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/GalBenZvi/papers-template/compare/v0.0.0...main



.. end-badges

A template repository for reproducing papers-related results.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install papers-template

You can also install the in-development version with::

    pip install https://github.com/GalBenZvi/papers-template/archive/main.zip


Documentation
=============


https://papers-template.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
