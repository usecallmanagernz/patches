[![Asterisk 20 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-20.yml?branch=master&label=asterisk%2020%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-20.yml) [![Asterisk 18 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-18.yml?branch=master&label=asterisk%2018%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-18.yml) [![Licence](https://img.shields.io/github/license/usecallmanagernz/patches?color=red)](LICENSE)

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

* Asterisk 20: [cisco-usecallmanager-20.12.0.patch](asterisk/cisco-usecallmanager-20.12.0.patch).
* Asterisk 18: [cisco-usecallmanager-18.26.0.patch](asterisk/cisco-usecallmanager-18.26.0.patch).

## OpenConnect Patch

Patches for OpenConnect are located in `ocserv` directory. These are
no longer required as support for the phone's VPN client was added
in version 1.2.0 and are only kept here for historical reference.
