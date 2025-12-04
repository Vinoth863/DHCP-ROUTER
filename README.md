# DHCP-ROUTER
DYNAMIC HOST CONFIGURATION POROTOCOL
# Definition
A DHCP-enabled router is a router configured to act as a Dynamic Host Configuration Protocol (DHCP) server, automatically assigning IP addresses, subnet masks, default gateways, and DNS information to devices on a LAN. This eliminates the need for manual IP configuration and ensures efficient network management.

# Project Definition
A single LAN network (192.168.0.0/24) was configured, and the router was set up as a DHCP server to automatically assign IP addresses, subnet masks, default gateways, and DNS settings to all connected devices, ensuring efficient IP management and network connectivity.

# DHCP BY ROUTER CLI COMMANDS

Router# config terminal

Router(config)# ip dhcp pool Lan1

Router(dhcp-config)# network 192.168.0.0 255.255.255.0

Router(dhcp-config)# default-router 192.168.0.1

exit
