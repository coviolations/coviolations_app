***************
.covio.yml file
***************

In this file you need to specifie project name and violations.
Example for django project:

.. code-block:: yaml

    violations:
      pep8: pep8 . --exclude='*migrations*'
      sloccount: sloccount .
