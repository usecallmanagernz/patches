[![Asterisk 20 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-20.yml?branch=master&label=asterisk%2020%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-20.yml) [![Asterisk 22 Build](https://img.shields.io/github/actions/workflow/status/usecallmanagernz/patches/asterisk-22.yml?branch=master&label=asterisk%2022%20build)](https://github.com/usecallmanagernz/patches/actions/workflows/asterisk-22.yml) [![Licence](https://img.shields.io/github/license/usecallmanagernz/patches?color=red)](LICENSE)

# Asterisk Patch

This repository contains patches for Asterisk that add support for
the features needed by Cisco Enterprise IP Phones. Only the latest
version of the patches should be used, the older versions are kept
here for historical reference.

Patches are only created for LTS versions of Asterisk.

See [Patching Asterisk](http://usecallmanager.nz/patching-asterisk.html)
for more information.

`chan_sip` was removed from the official Asterisk source in version 22 so
that version of the patch also contains a modernised version of the channel
driver.

As part of the version 22 some features have been removed as they are either
not supported by Cisco phones, are obsolete or are almost never enabled. See
[Version 22 ChangeLog](#Version-22-ChangeLog) for the full list.

**Note**: The patch for Asterisk 22 is currently in development and may not 
be suitable for production use.

## Latest Patch Versions

* Asterisk 20 (Stable): [cisco-usecallmanager-20.12.0.patch](asterisk/cisco-usecallmanager-20.12.0.patch).
* Asterisk 22 (Development): [cisco-usecallmanager-22.3.0.patch](asterisk/cisco-usecallmanager-22.3.0.patch).

## Version 22 ChangeLog

* Removed support for DTLS and WebSocket transports.
* Options `rpid_update` and `rpid_immediate` are now always enabled.
* Removed global options `insecure`, `allowguest`, `autocreatepeer`,
  `compactheaders`, `notifymime`, `snom_aoc_enabled` , `storesipcause`,
  `regcontext`, `regextenonqualify`, `legacy_option_parsing`
  `discard_hold_retrieval`.
* Removed peer options `username`, `callbackexten` and `regexten`.
* Removed DMTF mode INFO. Use either `rfc2833` or `inband`.
* Removed support the for `Also` header in BYE as this was replaced by
  the REFER method.
* Removed support for the `cpim-pidf-xml` events and Digium presence
  elements in dialog-info.
* Removed support for `call-completion`.
* Off-hook status for the peer is shown is available in the CLI and Manager.
* Outbound MWI subscriptions can now use TCP and TLS transports.

## OpenConnect Patch

Patches for OpenConnect are located in `ocserv` directory. These are
no longer required as support for the phone's VPN client was added in
version 1.2.0 and are only kept here for historical reference.
