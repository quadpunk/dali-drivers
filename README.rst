dali-drivers — lighting control interface drivers
=================================================

DALI ("Digital Addressable Lighting Interface") defines how lighting
control gear (eg. fluorescent ballasts, LED dimmers) and input devices
(push buttons, motion detectors, etc.) should interoperate.  It is
standardised in IEC 62386.

The `python-dali`_ project provides a driver-independent description
of the DALI protocol. This package provides drivers for some real DALI
interface hardware.

Python versions supported
-------------------------

This library currently requires Python version 3.10 or later.

Library structure
-----------------

- ``dalidrivers``

  - ``misc`` — Code to communicate with physical DALI gateways or
    services; code in this package does not have a standardised API

  - ``tests``

Contributors
------------

These drivers were originally contributed to the `python-dali`_
project, before being removed in release 1.0; this list of
contributors includes past contributors to that project.

- Stephen Early (Author)

- Robert Niederreiter

- Diogo Gomes

- Caiwan

- Boldie

- Martijn Hemeryck

- Hans Baumgartner

- Ferdinand Keil

- Sean Lanigan, Wallace Building Systems Pty Ltd

- Markus Becker

- Jan Kundrát

- Olivier Pieters

- David Russell

- Nikolay Korotkiy


Copyright
---------

dali-drivers is Copyright (C) 2013–2026 Stephen Early <steve@assorted.org.uk>
and other contributors.

It is distributed under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation, either version 3
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License and GNU General Public License along with this program.  If
not, see `this link`_.

.. _python-dali: https://github.com/sde1000/python-dali
.. _this link: https://www.gnu.org/licenses/
