[![Asterisk Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk.yml?branch=master&label=asterisk%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk.yml) [![Licence](https://img.shields.io/github/license/usecallmanagernz/patches?color=red)](LICENSE)

# Asterisk Patch

This repository contains patches for Asterisk that add support for
the features needed by Cisco Enterprise IP Phones.

Please note that only the latest version of the patches should be used,
the older versions are kept here for historical reference.

Patches are only created for LTS versions of Asterisk.

You only need to patch ocserv if you are planning on using the VPN
available on some phone models.

See [Patching Asterisk](http://usecallmanager.nz/patching-asterisk.html)
for more information.

## Latest Patch Versions

* Asterisk 20: [cisco-usecallmanager-20.04.0.patch](asterisk/cisco-usecallmanager-20.04.0.patch).
* Asterisk 18: [cisco-usecallmanager-18.19.0.patch](asterisk/cisco-usecallmanager-18.19.0.patch).

## OpenConnect Patch

Patches for OpenConnect are located in `ocserv` directory. These are
no longer required as support for the phone's VPN client was added
in version 1.2.0 and are kept here for historical reference.
