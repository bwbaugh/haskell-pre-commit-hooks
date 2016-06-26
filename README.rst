########################
Haskell pre-commit hooks
########################

Haskell related hooks
for use with the http://pre-commit.com/ framework.


*****
Hooks
*****

Most hooks can be installed with ``stack``.
If not already available,
`install stack
<http://docs.haskellstack.org/en/stable/README/#how-to-install>`_.
Then install the needed program
e.g., to install ``hlint`` run:

.. code-block:: bash

    stack --resolver=nightly --install-ghc install hlint

``hlint``
=========

`HLint <https://github.com/ndmitchell/hlint>`_
gives suggestions on how to improve your source code.

Install with stack.

``stylish-haskell``
===================

`stylish-haskell <https://github.com/jaspervdj/stylish-haskell>`_
is a code prettifier.

Install with stack.
