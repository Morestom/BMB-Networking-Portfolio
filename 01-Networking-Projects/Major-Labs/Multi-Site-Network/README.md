# Multi-site Network and Services

**Environment:** Cisco Packet Tracer  
**Project type:** Integrated routing, switching, and network services simulation

## Objective

Configure a simulated headquarters-and-branch network with segmented local networks, IP connectivity between sites, and essential network services.

## Configuration work

- Created VLANs to separate management, user, and server traffic.
- Configured trunk links to carry traffic for the required VLANs.
- Used OSPF to exchange routes and establish connectivity between networks.
- Configured a branch DHCP service to allocate host addressing information.
- Implemented NAT/PAT for traffic toward a simulated external network.
- Set up remote device access with SSH and Telnet, according to the exercise requirements.
- Applied switch port-security restrictions to a designated access interface.

## Verification

The submitted lab documentation records checks with `show vlan brief`, `show interfaces trunk`, `show ip ospf neighbor`, `show ip dhcp binding`, `show ip nat translations`, and `show port-security`, alongside end-to-end connectivity tests.

## Engineering focus

The exercise combined Layer 2 segmentation, Layer 3 routing, service configuration, and troubleshooting in one topology. It illustrates how individual configurations interact to provide end-to-end connectivity.

[← Networking projects](../../README.md)
