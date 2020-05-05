*****************************
Python Installation Guide
*****************************

Regardless of how you choose to install Python, please make sure you install Python version 3.x.  The latest increment
of version 3 is ideal.  `Python 2 is no longer supported <https://www.python.org/doc/sunset-python-2/>`_.  As part of
your educational experience, throughout class you will use `jupyter notebooks <https://jupyter.org/>`_, a programming environment that
runs in a web browser.  For this to work you will need a reasonably up-to-date browser, like the current
version of Chrome, Safari or Firefox.  For more information see the
`browsers supported by Jupyter <https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#browser-compatibility>`_.

We recommend the use of the `Anaconda distribution <https://www.anaconda.com/products/individual>`_ to maintain your
Python environment for most data science applications.  Python is currently the most popular data science language used
in industry.  A major reason it is an industry standard today is its diverse and well-maintained ecosystem of
packages.  Anaconda is essentially a bundle of many of these packages, and it comes with
`Conda <https://conda.io/docs/>`_, a package management system.

.. note::
    You do not need administrator or root permissions to install Anaconda if you select a user-writable install
    location.

Download the image or install script from https://www.anaconda.com/download/

On Ubuntu
==============

1. install via the command line

.. code-block::
    bash

    ~$ bash ~/Downloads/Anaconda3-2020.02-Linux-x86_64.sh

The above link may not have the same name as the actual file downloaded

.. important::
    Answer yes to questions that you are prompted with

2. Restart terminal

On OSX
========

1. Run the installer on the downloaded image

.. important::
    Answer yes to the path adding question

2. restart terminal

On Windows
===============

1. Ensure that you install the ``Anaconda installer for Windows`` for Python 3

2. Double-click the .exe file

3. Follow the instructions on the screen

If you are unsure about any setting, accept the defaults. You can change them later.
When installation is finished, from the Start menu, open the Anaconda Prompt.

.. important::
    Ensure that you check **Make Anaconda the default Python**

For more info, see https://conda.io/docs/user-guide/install/windows.html

Keeping conda up-to-date
=============================

.. code-block:: bash

    ~$ conda update --all

Troubleshooting
===================

Removing an old version
---------------------------

.. code-block::
   bash

   ~$ rm -rf ~/anaconda*

Additional Resources
===========================

* `Anaconda User Guide <https://docs.anaconda.com/anaconda/user-guide/>`_
* `To integrate Anaconda with an IDE <https://docs.anaconda.com/anaconda/user-guide/tasks/integration/>`_

