
Installation
============

Obtain sphinx-jsonschema by installing it with pip:

.. code-block:: bash

    sudo pip install sphinx-jsonschema

Then add it to your project by editing the ``conf.py`` file and
append 'sphinx-jsonschema' to the ``extensions`` array.

.. code-block:: python

    extensions = [
        'sphinx.ext.autodoc',
        'sphinx-jsonschema'
    ]

Source code
-----------

The source code for this extension can be found on `GitHub <https://github.com/lnoor/sphinx-jsonschema>`_.
