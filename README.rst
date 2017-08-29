========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/django-pony-banana/badge/?style=flat
    :target: https://readthedocs.org/projects/django-pony-banana
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/django-pony-banana.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/django-pony-banana

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/django-pony-banana?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/django-pony-banana

.. |requires| image:: https://requires.io/github/techdragon/django-pony-banana/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/django-pony-banana/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/techdragon/django-pony-banana/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/django-pony-banana

.. |landscape| image:: https://landscape.io/github/techdragon/django-pony-banana/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/django-pony-banana/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/django-pony-banana/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/django-pony-banana
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/django-pony-banana.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/django-pony-banana

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/django-pony-banana/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/django-pony-banana/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/django-pony-banana.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/django-pony-banana

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/django-pony-banana.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/django-pony-banana

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/django-pony-banana.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/django-pony-banana

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/django-pony-banana/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/django-pony-banana/


.. end-badges

Django Non-Rel revived, extended, and more!

* Free software: BSD license

Installation
============

::

    pip install django-pony-banana

Documentation
=============

https://django-pony-banana.readthedocs.io/

Development
===========

To run the all tests run::

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
