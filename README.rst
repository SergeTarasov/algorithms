Algorithms
==========

.. image:: https://travis-ci.org/nryoung/algorithms.svg?branch=master
    :target: https://travis-ci.org/nryoung/algorithms

.. image:: http://codecov.io/github/nryoung/algorithms/coverage.svg?branch=master
    :target: http://codecov.io/github/nryoung/algorithms?branch=master

Algorithms is a library of algorithms and data structures implemented in Python.

The main purpose of this library is to be an educational tool. You probably
shouldn't use these in production, instead, opting for the optimized versions of
these algorithms that can be found else where.

You should totally check out the docs for implementation details, complexities
and further info.

Usage
-----

If you want to use the algorithms in your code it is as simple as:

::

    from algorithms.sorting import bubble_sort

    my_list = bubble_sort.sort(my_list)

Features
--------

- Pseudo code, algorithm complexities and futher info with each algorithm.
- Test coverage for each algorithm and data structure.
- Super sweet documentation.

Installation:
-------------

Installation is as easy as:

::

    $ pip install algorithms


Tests:
------

Pytest is used as the main test runner and all Unit Tests can be run with:

::

    $ ./run_tests.py


Contributing:
-------------

Contributions are always welcome. Check out the contributing guidelines to get
started.
