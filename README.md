# ip-blocklist
IP addresses that have sent attacking or otherwise unwanted requests to my servers

The `list.txt` file contains numerous IPs and CIDR ranges of IP address and ISPs that have attacked, attempted to attack, or otherwise sent undesirable requests to my Internet-facing services, including web servers, Minecraft servers, and AdGuard Home instance. This list *will* contain false positives for likely harmless IP addresses. Many ranges come from https://github.com/ipverse/rir-ip and https://github.com/ipverse/asn-ip, as well as some manually blocked IPs and IP ranges.

This list is intended to be used as part of a server firewall and/or a disallowed clients list for AdGuard Home.

It is attempted to be kept free of duplicates and CIDRs merged

## Notable entities that are included in the list
- Brazil
- Russia
- China
- North Korea
- Alibaba
- Yandex
