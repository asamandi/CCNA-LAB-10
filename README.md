STP + EtherChannel (Port-Channel)

Goals:
------------------------------------
Spanning Tree Protocol behavior

Root bridge elections

Blocking/non-forwarding ports

EtherChannel (LACP) creation

Load-balancing on bundled links

TOPOLOGY:
------------------------------------
3 switches

Between each switch, there are 2 links.

Example:
------------------------------------
S1 ↔ S2 → (F0/1 & F0/2)

S2 ↔ S3 → (F0/3 & F0/4)

S1 ↔ S3 → (F0/5 & F0/6)

This gives us:
------------------------------------
STP redundancy

EtherChannel bundling
