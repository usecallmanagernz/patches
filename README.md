[![Asterisk Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk.yml?branch=master&label=asterisk%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk.yml) [![OCServ Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/ocserv.yml?branch=master&label=ocserv%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/ocserv.yml) [![Licence](https://img.shields.io/github/license/usecallmanagernz/patches?color=red)](LICENSE)

# Asterisk and Ocserv Patches

This repository contains patches for Asterisk and OpenConnect Server
(ocserv) that add support for the features needed by Cisco Enterprise
IP Phones.

Please note that only the latest version of the patches should be used,
the older versions are kept here for historical reference.

Patches are only created for LTS versions of Asterisk.

You only need to patch ocserv if you are planning on using the VPN
available on some phone models.

See [Patching Asterisk](http://usecallmanager.nz/patching-asterisk.html)
and [VPN Connection](http://usecallmanager.nz/vpn-group.html) for more
information.

## Latest Patch Versions

* Asterisk 18: [cisco-usecallmanager-18.16.0.patch](asterisk/cisco-usecallmanager-18.16.0.patch).
* OCServ: [cisco-webvpnlogin-1.1.6.patch](ocserv/cisco-webvpnlogin-1.1.6.patch).
