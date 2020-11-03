---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

id: bitbox
title: "BitBox02"
titleshort: "BitBox02"
compat: "hardware"
level: 2
platform:
  - hardware:
    name: hardware
    os:
      - name: hardware
        text: "walletbitbox"
        link: "https://shiftcrypto.ch/bitbox02/"
        source: "https://github.com/digitalbitbox/bitbox02-firmware"
        screenshot: "bitbox02.png"
        features: "bech32 hardware_wallet legacy_addresses segwit"
        check:
          hardware:
            environment: "checkgoodenvironmenthardware"
            transparency: "checkgoodtransparencydeterministic"
            control: "checkgoodcontrolfull"
          app:
            validation: "checkneutralvalidationvariable"
            privacy: "checkpassprivacynetworksupporttorproxy"
            fees: "checkgoodfeecontrolfull"
---
