cdist-type__ungleich_cdist_user(7)
==================================
Manage NTP client

ungleich GmbH <cdist--@--ungleich.ch>


DESCRIPTION
-----------
This cdist type creates a user with a cdist installation


OPTIONAL PARAMETER
------------------
state
    present or absent, defaults to present

shell
    zsh or bash, defaults to zsh


EXAMPLES
--------

.. code-block:: sh

    # create user named cdist with cdist installation
    __ungleich_cdist_user cdist

    # Use bash as shell instead
    __ungleich_cdist_user cdist --shell bash

    # Remove cdist user
    __ungleich_cdist_user cdist --state absent



SEE ALSO
--------
- `cdist-type(7) <cdist-type.html>`_


COPYING
-------
Copyright \(C) 2014 ungleich GmbH (www.ungleich.ch). 
Free use of this software is granted under the terms 
of the GNU General Public License version 3 (GPLv3).
