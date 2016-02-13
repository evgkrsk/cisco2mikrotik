# cisco2mikrotik
Cisco to Mikrotik configuration converter

# Language
python2

# License
GPLv3+

# Usage
run ./cisco2mikrotik --help for info

# Requires
* <https://github.com/mpenning/ciscoconfparse>
* <https://github.com/google/ipaddr-py>

# Supported features
* Loopback\*, \*Ethernet, Dot1q-subinterfaces (not shutdowned and not in vrf-s)
* interface descriptions
* manual interface names mapping
* IPv4 addresses
* manual IPv4 addreses mapping
* IPv4 static routes
* input/output ACL-s (standard/extented) on interfaces
* local users (with passwords where possible)
