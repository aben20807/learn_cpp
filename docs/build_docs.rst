Build docs
=============

Environment
~~~~~~~~~~~

+ Ubuntu 18.04

.. code-block:: bash

    $ virtualenv env -p python3.6
    $ source env/bin/activate
    $ pip install sphinx sphinx_rtd_theme sphinx-autobuild restructuredtext-lint

Develop
~~~~~~~

.. code-block:: bash

    $ sphinx-autobuild -a docs docs/_build/html
    $ # Open http://127.0.0.1:8000/ in browser