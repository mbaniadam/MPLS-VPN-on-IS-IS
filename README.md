# MPLS VPN Implementation with IS-IS Routing Protocol

#### This repository contains the implementation of a Multi-Protocol Label Switching (MPLS) Virtual Private Network (VPN) using the Intermediate System to Intermediate System (IS-IS) routing protocol in a service provider network. The setup includes two customers with three sites each, interconnected through the provider network. The following technologies and protocols are utilized in this implementation:

**IS-IS Routing Protocol**: IS-IS is used on the provider routers to establish the core routing infrastructure.

**MPLS Network**: MPLS is enabled on the provider routers to create a label-switched network that facilitates efficient packet forwarding.

**MPLS-VPN**: MPLS-VPN is employed to provide secure and isolated communication between multiple customer sites.

**MP-BGP**: Multi-Protocol Border Gateway Protocol (MP-BGP) is used to carry VPNv4 routes between the Provider Edge (PE) routers.

**BGP**: BGP is utilized as the exterior routing protocol for exchanging routes between the provider network and the customer edge (CE) routers.

**iBGP**: Internal BGP (iBGP) is employed for BGP route distribution within the provider network.

**Route Reflector**: Route Reflectors are used to reduce the complexity of iBGP full mesh configuration, improving scalability.

**OSPF, EIGRP, and BGP**: These routing protocols are used for CE-PE routing, connecting the customer sites to the provider network.

![image](https://github.com/mbaniadam/MPLS-VPN-on-IS-IS/assets/75830370/8f36efad-fa42-4513-8cee-444d4b27d301)


