# Switching and WAN Routing

**Environment:** Cisco Packet Tracer  
**Project type:** Multi-site switching and routing simulation

## Objective

Establish communication across a simulated campus-and-branch topology while applying switching, WAN, dynamic routing, and device management configurations.

## Configuration work

- Used VTP to propagate the VLAN database to a client switch.
- Configured Spanning Tree root-bridge selection for the relevant VLANs.
- Established simulated Frame Relay connections among routers.
- Enabled EIGRP to exchange routing information between the core and branch networks.
- Configured remote device administration with SSH and Telnet.
- Applied PAT for simulated access to an external network.

## Verification

The lab report includes `show vtp status`, `show spanning-tree`, `show frame-relay map`, `show ip eigrp neighbors`, and `show ip nat translations`, along with ping and remote-access tests.

## Engineering focus

The project integrated switch control-plane features with WAN connectivity and dynamic routing. The verification work examined both protocol state and actual reachability between connected sites.

[← Networking projects](../../README.md)
