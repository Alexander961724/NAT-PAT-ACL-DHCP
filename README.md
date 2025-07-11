# NAT-PAT-ACL-DHCP
Small Lab with NAT, PAT, ACL and DHCP, moreover a small troubleshooting, due to missconfigured ACL. 
## 📷 Network Diagram
![Network Topology](TOPOLOGY.png) 

## 📄 DHCP Pools en el Router:
![Network Topology](0-DHCP-POOLS-R1.png) 

## 📝 Router Subinterfaces + NAT/PAT + ACLs:
Interface Ethernet0/0
![Network Topology](1-ETH0-0-CON-EXTERNAL-NOSHUT.png) 
Interface Ethernet0/1 
![Network Topology](2-ETH0-1-NOSHUT.png) 

## ✅ NAT Overload PAT:
![Network Topology](3-NAT-OVERLOAD.png)

##🖲️ ACL bloquea tráfico entre VLANs pero permitir acceso a Internet:
![Network Topology](4-ACL-BLOCK-VLANS.png)

## 🧬 Switch Config VLANs + Trunk:
![Network Topology](5-VLAN,CREATION.TRUNKING MODE.png)
Interfaces VLAN 
![Network Topology](6-INTERFACES-ACCESS-VLANS.png)

