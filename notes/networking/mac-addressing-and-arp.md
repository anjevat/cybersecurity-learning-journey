# MAC Addressing and ARP

## MAC Address

A MAC (Media Access Control) address is a unique hardware address assigned to a network interface.

Example:

00:1A:2B:3C:4D:5E

MAC addresses operate mainly at the Data Link layer of the OSI model.

## ARP

ARP (Address Resolution Protocol) is used to discover the MAC address associated with an IPv4 address on a local network.

### Basic Process

1. A device knows the destination IP address.
2. It broadcasts an ARP request asking who owns that IP.
3. The device with that IP sends an ARP reply containing its MAC address.
4. The requesting device stores the information in its ARP cache.

## Security Relevance

ARP is important in cybersecurity because attackers can abuse ARP through techniques such as ARP spoofing/poisoning to redirect network traffic.

## Key Point

IP addresses identify devices logically, while MAC addresses identify network interfaces at the local network level.
