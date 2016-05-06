########################
Haskell pre-commit hooks
########################

Haskell related hooks
for use with the http://pre-commit.com/ framework.


*****
Hooks
*****

``hlint``
=========

`HLint <https://github.com/ndmitchell/hlint>`_
gives suggestions on how to improve your source code.

Installation
------------

The ``hlint`` executable must be available on your path.
If not already available,
`install stack
<http://docs.haskellstack.org/en/stable/README/#how-to-install>`_
then install HLint:

.. code-block:: bash

    stack setup
    stack install hlint
