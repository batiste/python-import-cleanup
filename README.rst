=======================
python-import-cleanup
=======================

This simple script assist you in removing unecessary import statement from your source code.

Usage
============

First install pyflakes to find unused import::

    $ sudo pip install pyflakes

Then create the pyflakes output::

    $ pyflakes <your package> > out.flakes

Finaly, execute the cleanup script::

    $ python cleanup_import.py


For every import, the script will ask you if you want to remove the statement.
The real changes are only done at the end of the statement review.