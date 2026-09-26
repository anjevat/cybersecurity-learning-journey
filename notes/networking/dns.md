# DNS (Domain Name System)

## Overview

DNS is a system that translates human-readable domain names into IP addresses that computers use to communicate.

Example:

www.example.com → 93.184.216.34

## How DNS Works

1. A user enters a domain name.
2. The device sends a DNS query.
3. A DNS server looks up the corresponding IP address.
4. The IP address is returned to the device.
5. The device connects to the destination server.

## Common DNS Record Types

- **A** — Maps a domain name to an IPv4 address.
- **AAAA** — Maps a domain name to an IPv6 address.
- **CNAME** — Creates an alias for another domain name.
- **MX** — Specifies mail servers for a domain.
- **NS** — Identifies authoritative name servers.

## Security Relevance

DNS is important in cybersecurity because attackers can abuse DNS through techniques such as DNS spoofing, DNS tunneling, and malicious domain infrastructure.

## Key Point

DNS makes it possible to access network services using memorable domain names instead of remembering IP addresses.
