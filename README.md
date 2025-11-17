[![Asterisk 20 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-20.yml?branch=master&label=asterisk%2020%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-20.yml) [![Asterisk 22 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-22.yml?branch=master&label=asterisk%2022%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-22.yml) [![Licence](https://img.shields.io/github/license/usecallmanagernz/patches?color=red)](LICENSE)

# Asterisk Patch

This repository contains patches for Asterisk that add support for the features
needed by Cisco Enterprise IP Phones. Only the latest version of the patches
should be used, the older versions are kept here for historical reference.

Patches are only created for LTS versions of Asterisk.

See [Patching Asterisk](https://usecallmanager.nz/patching-asterisk.html)
for more information.

**Note:** `chan_sip` was removed from the official Asterisk source in version 22
so that version of the patch also contains a modernised version of the channel
driver. Obsolete features have been removed and many configuration options have
been renamed, see the
[Change Log](https://usecallmanager.nz/change-log.html)
for the full list.

**Note**: The patch for Asterisk 22 is **ready for testing** and may not be
suitable for production use.

## Latest Patch Versions

* Asterisk 20 (Stable): [cisco-usecallmanager-20.16.0.patch](asterisk/cisco-usecallmanager-20.16.0.patch).
* Asterisk 22 (Ready for Testing): [cisco-usecallmanager-22.6.0.patch](asterisk/cisco-usecallmanager-22.6.0.patch).

## OpenConnect Patch

Patches for OpenConnect are located in `ocserv` directory. These are no longer
required as support for the phone's VPN client was added in version `1.2.0` and
are only kept here for historical reference.
