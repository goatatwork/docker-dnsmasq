This is a dnsmasq install on Alpine Linux. The default
`/etc/dnsmasq.conf` file is configured as a resolver with DNSSEC and
log-queries enabled.

To make life a little easier, there is a `reference-dnsmasq.conf` file in `/etc`
that is a copy of the config file from the installation. It isn't loaded and is
there only for reference.

Here are the build details for the Dnsmasq daemon.
```
Dnsmasq version 2.84rc2  Copyright (c) 2000-2021 Simon Kelley
Compile time options: IPv6 GNU-getopt no-DBus no-UBus no-i18n no-IDN DHCP DHCPv6 no-Lua TFTP no-conntrack ipset auth cryptohash DNSSEC loop-detect inotify dumpfile
```
