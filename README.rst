|PyPI| |Test| |Gitter| |DOI| |binder|

.. |PyPI| image:: https://img.shields.io/pypi/v/folium.svg
    :target: https://pypi.org/project/folium
    :alt: PyPI Package

.. |Test| image:: https://github.com/python-visualization/folium/actions/workflows/test_code.yml/badge.svg
    :target: https://github.com/python-visualization/folium/actions/workflows/test_code.yml
    :alt: Code tests

.. |Gitter| image:: https://badges.gitter.im/python-visualization/folium.svg
    :target: https://gitter.im/python-visualization/folium
    :alt: Gitter

.. |DOI| image:: https://zenodo.org/badge/18669/python-visualization/folium.svg
   :target: https://zenodo.org/badge/latestdoi/18669/python-visualization/folium
   :alt: DOI
   
.. |binder| image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/python-visualization/folium/main?filepath=examples

folium
======

|folium|

Python Data, Leaflet.js Maps
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`folium` builds on the data wrangling strengths of the Python ecosystem and the
mapping strengths of the Leaflet.js library. Manipulate your data in Python, 
then visualize it in a Leaflet map via `folium`.

Windows Build
------------

.. code:: cmd

    > python setup.py bdist_wheel


RPM Build
.. code:: bash

    $ docker run --rm -t -v %cd%:/project redhat/ubi8:8.6 bash -c "yum install -y rpm-build python3 && cd /project && python3 setup.py bdist_rpm"


Installation
------------

.. code:: bash

    $ pip install folium

or

.. code:: bash

    $ conda install -c conda-forge folium

Documentation
-------------

https://python-visualization.github.io/folium/


Gallery
-------

There are two galleries of Jupyter notebooks with examples, which you can see
using Jupyter's nbviewer:

https://nbviewer.jupyter.org/github/python-visualization/folium/tree/main/examples/

https://nbviewer.jupyter.org/github/python-visualization/folium_contrib/tree/master/notebooks/

Contributing
------------

We love contributions!  folium is open source, built on open source,
and we'd love to have you hang out in our community.

See `our complete contributor's guide <https://github.com/python-visualization/folium/blob/main/.github/CONTRIBUTING.md>`_ for more info.


.. |folium| image:: http://python-visualization.github.io/folium/_images/folium_logo.jpg



Changelog
---------

Check the `changelog <https://raw.githubusercontent.com/python-visualization/folium/main/CHANGES.txt>`_ for a detailed list of the latest changes.
