# ComputerNetworksAttack
Project still in progress. 
User can choose two ips of the victims, the code executes an arp poisoning fixing the attacker as the man in the middle, followed by either a dns spoof, that redirects the user to a website of the attacker's choosing, or a ssl strip that redirects the user to a website of the attacker's choosing, while the attacker establishes a secure channel with the server (secure channel still to be implemented). More to come in the following days..

## Requirements
1. Linux machine
2. Python 3
3. Scapy library
4. Netfilter library
5. Enable ipv4 packet forwarding in sysctl.conf of the linux machine found in /etc.
