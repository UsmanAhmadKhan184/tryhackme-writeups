# DNS in Detail

## Overview
DNS (Domain Name System) translates human-readable
domain names into IP addresses so computers can
communicate over the network.

## How DNS Works
1. User enters a domain name (e.g., google.com)
2. DNS resolver checks cache
3. Query is sent to DNS servers if not cached
4. IP address is returned to the user

## Domain Hierarchy
- **TLD (Top-Level Domain)** – The most righthand part of a domain name. For example, the github.com TLD is .com.
- **Second-Level Domain** – Taking github.com as an example, the .com part is TLD, and github is the Second Level Domain.
- **Subdomain** – A subdomain is on the left-hand side of the Second-Level Domain; for example, in the name admin.github.com the admin part is the subdomain.

## Common DNS Record Types
- **A** – Maps domain to IPv4 address
- **AAAA** – Maps domain to IPv6 address
- **CNAME** – Alias for another domain
- **MX** – Mail server records
- **TXT** – Stores text-based information

## What I Learned
- DNS is critical for internet communication
- Misconfigured DNS can be exploited
- DNS traffic can reveal valuable information

## Why This Matters in Cybersecurity
DNS is often abused for:
- Phishing attacks
- Command and Control (C2)
- Data exfiltration

## Key Takeaway
Understanding DNS helps identify malicious domains
and prevent network-based attacks.
