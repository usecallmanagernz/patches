[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/usecallmanagernz/patches/asterisk-18%20build/master?label=asterisk-18%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-18.yml) [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/usecallmanagernz/patches/asterisk-16%20build/master?label=asterisk-16%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-16.yml) [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/usecallmanagernz/patches/ocserv%20build/master?label=ocserv%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/ocserv.yml)

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

* Asterisk 18: [cisco-usecallmanager-18.5.0.patch](asterisk/cisco-usecallmanager-18.5.0.patch).
* Asterisk 16: [cisco-usecallmanager-16.19.0.patch](asterisk/cisco-usecallmanager-16.19.0.patch).
* Asterisk 13: [cisco-usecallmanager-13.38.2.patch](asterisk/cisco-usecallmanager-13.38.2.patch).
* OCServ: [cisco-webvpnlogin-1.1.3.patch](ocserv/cisco-webvpnlogin-1.1.3.patch).
