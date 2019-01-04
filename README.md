VASCO VACMAN Controller
=======================

VACMAN Controller is VASCO's implementation of OTP physical and virtual devices, revolving around the AAL2 library.

This gem contains a very thin wrapper around AAL2 and allows to parse DPX files, generate OTPs and verify them.

Installation
------------

Get Vacman Controller library from the [TrustBuilder repo](https://repository.trustbuilder.io/head/trustbuilder/custom/), download the `aal2sdk-*.rpm` and place its contents in `/opt/vasco`. The Ruby extension looks for `/opt/vasco/VACMAN_Controller-*`

Then you can use

    rake install

to build and install the gem, or

    rake compile

to generate the Makefile and compile it.

To run specs, execute

    rspec
