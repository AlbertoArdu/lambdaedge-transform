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
.. |docs| image:: https://readthedocs.org/projects/lambdaedge-transform/badge/?style=flat
    :target: https://lambdaedge-transform.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/AlbertoArdu/lambdaedge-transform/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/AlbertoArdu/lambdaedge-transform/actions

.. |requires| image:: https://requires.io/github/AlbertoArdu/lambdaedge-transform/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/AlbertoArdu/lambdaedge-transform/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/AlbertoArdu/lambdaedge-transform/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/AlbertoArdu/lambdaedge-transform

.. |version| image:: https://img.shields.io/pypi/v/lambdaedge-transform.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/lambdaedge-transform

.. |wheel| image:: https://img.shields.io/pypi/wheel/lambdaedge-transform.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/lambdaedge-transform

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/lambdaedge-transform.svg
    :alt: Supported versions
    :target: https://pypi.org/project/lambdaedge-transform

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/lambdaedge-transform.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/lambdaedge-transform

.. |commits-since| image:: https://img.shields.io/github/commits-since/AlbertoArdu/lambdaedge-transform/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/AlbertoArdu/lambdaedge-transform/compare/v0.0.0...master



.. end-badges

Python module to simplify transformation of requests and responses on Lambda@Edge.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install lambdaedge-transform

You can also install the in-development version with::

    pip install https://github.com/AlbertoArdu/lambdaedge-transform/archive/master.zip


Documentation
=============


https://lambdaedge-transform.readthedocs.io/


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
