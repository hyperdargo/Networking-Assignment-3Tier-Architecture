# Three-Tier Network Configuration

This repository contains the configuration files and documentation for a **Three-Tier Network Architecture** implementation. The project focuses on setting up **SVI**, **NAT**, and **PAT** on a multilayer switch, along with other critical network services.

## Project Overview
- **Objective:** Implement a resilient three-tier network architecture for headquarters and branch locations.
- **Technologies Used:** Cisco Packet Tracer, Multilayer Switch, VLANs, DHCP, HSRP, Spanning Tree, VPN, NAT, PAT.
- **Key Features:**
  - Configuration of SVIs for inter-VLAN routing.
  - Implementation of NAT and PAT for internet access.
  - Integration of emerging technologies like SDN and cloud computing.

## Files Included
1. **Three-Tier-Network.pkt**: Packet Tracer file containing the network setup.
2. **Network-Configuration-Report.pdf**: Detailed report explaining the configuration steps and verification.
3. **Screenshots/**: Folder containing screenshots of the final configuration and verification commands.

## How to Use
1. Open the `Three-Tier-Network.pkt` file in Cisco Packet Tracer.
2. Refer to the `Network-Configuration-Report.pdf` for step-by-step instructions.
3. Check the `Screenshots/` folder for visual verification of the setup.

## Verification
To verify the configuration, use the following commands:
- `show ip interface brief`
- `show vlan brief`
- `show ip route`
- `show ip nat translations`
- `show ip nat statistics`

## Author
[Your Name]  
[Your Contact Information]

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
