============
Installation
============


Requirements
------------
    * Python 2.7 or Python 3.4+


Platforms
---------
py_entitymatching has been tested on Linux (Redhat enterprise Linux with 2.6
.32 kernel), OSX (Sierra), and Windows 10.


Dependencies
------------
    * pandas (provides data structures to store and manage relational data)
    * scikit-learn (provides implementations for common ML algorithms)
    * joblib (provides multiprocessing capabilities)
    * PyQt4 (provides tools to build GUI)
    * py_stringsimjoin (provides implementations for string similarity joins)
    * py_stringmatching (provides a set of tokenizers and string similarity functions)
    * cloudpickle (provides functions to serialize Python constructs)
    * pyprind (library to display progress indicators)
    * pyparsing (library to parse strings.)
    * six (provides functions to write compatible code across Python 2 and 3)

There are three ways to install py_entitymatching package: (1) using conda,
(2) using pip , and (3) using source distribution.

Installing Using conda
----------------------
The easiest and the recommended way to install the package is to use conda,
which will retrieve py_entitymatching from Anaconda repository then install it::

    conda install -c uwmagellan py_entitymatching

.. note::
    The above command will install py_entitymatching and all its dependencies.

.. note::
    To use conda command, first you must install Miniconda or Anaconda. For
    more details refer to this `conda page <http://conda.pydata
    .org/docs/using/index
    .html>`_.


Installing Using pip
--------------------
To install the py_entitymatching package using pip, execute the following
command::

    pip install py_entitymatching

.. note::
    The above command will install py_entitymatching and all its
    dependencies, except PyQt4. Refer to this `PyQt4 page <http://pyqt.sourceforge
    .net/Docs/PyQt4/installation.html>`_ to install
    PyQt4.



Installing from Source Distribution
-----------------------------------
Step 1: Download the py_stringmatching package from `here
<https://sites.google.com/site/anhaidgroup/projects/py_entitymatching>`_.

Step 2: Unzip the package and execute the following command from the package
root::

    python setup.py install

.. note::

    The above command will try to install py_stringmatching into the default
    Python directory on your machine. If you do not have installation
    permission for that directory then you can install the package in your
    home directory as follows::

        python setup.py install --user

    For more information see the StackOverflow `link
    <http://stackoverflow.com/questions/14179941/how-to-install-python-packages-without-root-privileges>`_.

.. note::

    The above command will install py_entitymatching and all its
    dependencies, except PyQt4.
    Refer to this `page
    <http://pyqt.sourceforge.net/Docs/PyQt4/installation.html>`_ to install
    PyQt4.



