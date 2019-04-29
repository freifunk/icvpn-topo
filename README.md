icvpn-topo
==========

current state: not maintained

Topology Graphs about Freifunk Intercity VPN

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

Because tinc version 1.1pre10 does not provide dot information anymore, two tinc files must be
added to tinc configuration. These files collect the peer names which are used by the script to
generate the graph (without connection between nodes)


