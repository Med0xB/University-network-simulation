# University-network-simulation
This is a Campus LAN network design connecting three buildings using VLAN segmentation, Inter-VLAN Routing, DHCP, ACLs, and SSH access.

🏢 Campus Structure

Three departments/buildings are connected via a core switch:

Administration (VLAN 10)

Guest Hall Wi-Fi Zone (VLAN 20)

Computer Science Department (VLAN 30)

Information Technology Department (VLAN 40)


🛠 Technologies Used

Cisco Packet Tracer for simulation

VLANs for segmentation

802.1Q Trunking to carry multiple VLANs

Inter-VLAN Routing via a router (Router-on-a-Stick model)

DHCP server for dynamic IP assignment (VLAN 20)

SSH access enabled on router for secure management

ACLs to restrict inter-VLAN access and enhance security


🔐 Security Logic (ACLs)

VLAN 20 (Guest Hall) is isolated: Cannot access any other VLAN


✅ Outcomes

Efficient segmentation for organization and control

Secure inter-VLAN communication with restricted access

Scalability for future departments and services

Realistic simulation of a professional enterprise network


