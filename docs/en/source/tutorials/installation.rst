.. _installation:

=============
Installation
=============

Let's get started by setting up our environment to run this snake.

Requirements
~~~~~~~~~~~~

The baby version of cobra is sensitive, and it could only be happy when living with python 3.7 or newer. So please set a nice environment to make sure it is happy.

Working environment
~~~~~~~~~~~~~~~~~~~

COBRA is tested and supported on the following 64-bit systems:
- python 3.7
- linux

You will have two options to keep cobra happy:

- using docker
- building up own working environment

See more details from :ref:`environment`.

Install COBRA
~~~~~~~~~~~~~~~~~~
Users are welcome to install COBRA either use ``pip package`` or ``build from source``.

``pip`` package manager
--------------------------

Install COBRA with Python's ``pip`` package manager.
.. highlight:: sh

::

   # Requires the latest pip
   pip install --upgrade pip
   # Current stable release
   pip install sslab-cobra
   
Build from source
--------------------------

Download the COBRA source code from github

.. highlight:: sh

::

   # git clone
   git clone https://github.com/ss-lab/cobra.git
   cd cobra
   
   # build environment
   pip install -r requirements.txt
   python setup.py install


