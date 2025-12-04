# DHCP-ROUTER
DYNAMIC HOST CONFIGURATION POROTOCOL
A single LAN network (192.168.0.0/24) was configured, and the router was set up as a DHCP server to automatically assign IP addresses, subnet masks, default gateways, and DNS settings to all connected devices, ensuring efficient IP management and network connectivity.

# DHCP BY ROUTER CLI COMMANDS

Router# config terminal

Router(config)# ip dhcp pool Lan1

Router(dhcp-config)# network 192.168.0.0 255.255.255.0

Router(dhcp-config)# default-router 192.168.0.1

exit
