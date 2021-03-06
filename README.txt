WorldMill
=========

WorldMill provides a smoother and more productive Python interface to the open
source GIS community's most trusted geodata access library; doing for libgdal_
what lxml does for libxml2. WorldMill integrates readily with other Python GIS
packages such as pyproj_, Rtree_, and Shapely_.

Dependencies
------------

WorldMill requires libgdal 1.3.2+.

Building
--------

From the distribution root::

  $ virtualenv .
  $ python setup.py test

or if you have nose::

  $ virtualenv .
  $ python setup.py develop
  $ nosetests tests
  
If you have ogr.py installed, you can compare to WorldMill::

  $ python benchmark.py

Usage
-----

See `docs/reading-data.txt`_ for examples.

.. _libgdal: http://www.gdal.org
.. _pyproj: http://pypi.python.org/pypi/pyproj/
.. _Rtree: http://pypi.python.org/pypi/Rtree/
.. _Shapely: http://pypi.python.org/pypi/Shapely/
.. _docs/reading-data.txt: http://trac.gispython.org/projects/PCL/browser/WorldMill/trunk/docs/reading-data.txt
