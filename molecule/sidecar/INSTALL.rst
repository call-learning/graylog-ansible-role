*******
Docker driver installation guide
*******

Requirements
============

* Docker Engine

Install
=======

Please refer to the `Virtual environment`_ documentation for installation best
practices. If not using a virtual environment, please consider passing the
widely recommended `'--user' flag`_ when invoking ``pip``.

.. _Virtual environment: https://virtualenv.pypa.io/en/latest/
.. _'--user' flag: https://packaging.python.org/tutorials/installing-packages/#installing-to-the-user-site

.. code-block:: bash

    $ python3 -m pip install 'molecule[docker]'


Local usage
===========

You can use this as a test install by just bringing up the test server.

    molecule converge

Then setup your web browser to go through the localhost:10080 web proxy and
you should be able to get the UI of Graylog.
The user is 'admin', password is 'password'.
