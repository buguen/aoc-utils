Viewer executable

Topology executable

Bounding box executable


BUGS
====

- 1 test related to analyze/bounds.py BetterBoundingBox not passing ( test_better_bounds_complex_shape())


EVOLUTIONS & ENHANCEMENTS
=========================

General
-------
-> pypi (see http://peterdowns.com/posts/first-time-with-pypi.html)
    DELETE FROM PYPI -> MOVE TO ANACONDA (make sure all dependencies are included in the recipe)
-> CI
-> Coverage
it is a library, easy on logging (debug for almost everything, info if very important)

Get rid of asserts

OCC imports

Tolerance management.

tests
-----
*_make.py
operations
geom

Python 3 tests

analyze
-------
global properties of compound

operations/boolean
------------------
Volume / area of compounds -> what is current behaviour? what is desired behaviour?
cleaner boolean functions

examples
--------
add example with handles ...
example using adaptors
operations

examples/geomplate.py
---------------------
- need examples where the tangency to constraining faces is respected
- fix build_curve_network()

_fixme/triangulation.py
-----------------------
Unexpected results :  3 vertexes, 1 edge, 0 triangle from a face ?
