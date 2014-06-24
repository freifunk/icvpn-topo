icvpn-topo
==========

Topology Graphs about Freifunk Intercity VPN

Live view at http://www.freifunk-dresden.de/topology/ic-vpn-verbindungen.html


The script contains several path variables that should be adapted.
It uses the generated tinc dot file and the bgpd.conf to get needed information.
It is important that the city names in bgp.conf uses same names as used in tinc host descriptions
because the topology and bgpd clients must match.

I had to modify the bgpd.conf because names are different:
Franken1 to franken_ro1
kiberpipa.net to ljubljana1
diac24.net to diac24_sbz

Directory example-files contains files that are used to produce output. Please look for the file names
in script to know where they are used.


