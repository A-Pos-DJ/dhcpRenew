#Run command with no arguments to reset all non-loopback interfaces (Default 3 second wait before attempting top renew DHCP) 

#Command Options:
# 1) Argument interface name to reset that specific interface address (returns with error message if interface is not found)
# 2) Argument amount of time in seconds (Integer) to kill the process on all interfaces, wait (your argument) number of seconds, then renew the address on all interfaces (Kills and renews one interface at a time)
# 3) Argument the interface name and then argument amount of time in seconds (Integer) you would like to wait before another address is assigned via DHCP
