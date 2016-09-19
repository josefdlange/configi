Configi
=======

Configi is a straightforward wrapper for configuration data. It provides a consistent interface to a number of back-ends, currently via arbitrary HTTP JSON loading, Redis K/V store, and S3 JSON file loading.

Using Configi
-------------

The code itself is documented, but here's a couple of recipes:

.. code-block:: python

	from configi import DynamicConfig, S3ConfigSource

	