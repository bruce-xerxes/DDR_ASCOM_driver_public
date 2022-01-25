DDR_ASCOM_driver_public

Publicly available ASCOM driver for ethernet datagram based telescope mount control
by Xerxes Scientific, LLC.
Copyright (C) Xerxes Scientific, LLC 2021

This directory contains:
XerxesD111 Setup.exe - installer for the ASCOM driver named D11test.Telescope
ASCOM.XerxesD11test.telescope.dll - this is the actual dll file that gets installed in the
following location:
C:\Program Files(x86)\Common Files\ASCOM\Telescope
along with all your other ASCOM telescope (mount) drivers.

If the installer fails to update this file, you can do so manually by copying it here.
The GUID is 54ce484c-c0d5-4741-a67a-83ea407fac6d which you may need if you end up using regedit manually.
