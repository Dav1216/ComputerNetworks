# ComputerNetworksAttack
Project still in progress. 
User can choose two ips of the victims, the code executes an arp poisoning fixing the attacker as the man in the middle, followed by either a dns spoof, that redirects the user to a website of the attacker's choosing, or a ssl strip that redirects the user to a website of the attacker's choosing, while the attacker establishes a secure channel with the server (secure channel still to be implemented). More to come in the following days including a video demonstration using virtual machines a bind9 dns server and an apache2 webserver that will suport ssl.

## Requirements
1. Linux machine
2. Weberver that supports SSL
3. Another webserver that hosts a website
4. A dns server
5. Python 3
6. Scapy library
7. Netfilter library
8. Enable ipv4 packet forwarding in sysctl.conf of the linux machine found in /etc.
