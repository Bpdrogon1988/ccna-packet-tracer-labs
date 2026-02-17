# CCNA Packet Tracer Labs Portfolio

This repository is my centralized CCNA Packet Tracer lab portfolio.

Its purpose is to document hands-on networking practice across core switching and routing objectives, with an emphasis on:

- VLAN segmentation and access-port assignment
- 802.1Q trunking and DTP behavior
- Inter-VLAN routing (router-on-a-stick and Layer 3 switching)
- Redundancy and stability (STP and EtherChannel)
- Foundational infrastructure services (DHCPv4, interface addressing, and SSH hardening)

## Lab Inventory

> File names are kept as exported/submitted for class tracking, so some include spaces and assignment identifiers.

| # | Lab File | Primary Topic | Competencies Demonstrated |
|---|---|---|---|
| 1 | `BrandenPT.pka kier_PT3.3.12-packet-tracer---vlan-configuration.pka` | VLAN Configuration | Created VLANs, assigned access ports, validated segmentation and broadcast-domain separation. |
| 2 | `BrandenF_PT.pka kier_PT3.4.5ai Packet Tracer - Configure Trunks.pka` | Trunking (802.1Q) | Configured trunks between switches, validated allowed VLAN propagation, and confirmed encapsulation behavior. |
| 3 | `BrandenF_PT.pka kier_PT 3.5.5aiPacket Tracer - Configure DTP.pka` | DTP Negotiation | Managed dynamic trunk negotiation, controlled trunk/access outcomes, and enforced deterministic switchport mode design. |
| 4 | `BrandenF_PT.pka kier_PT 4.2.7-packet-tracer---configure-router-on-a-stick-inter-vlan-routing.pka` | Inter-VLAN Routing (Router-on-a-Stick) | Built subinterfaces, applied dot1Q tagging, and routed traffic between VLANs through a single trunk link. |
| 5 | `BrandenF_PT.pka kier_PT 4.3.8-packet-tracer---configure-layer-3-switching-and-inter-vlan-routing.pka` | Inter-VLAN Routing (L3 Switch) | Enabled SVIs and multilayer routing to move inter-VLAN traffic at switch layer while preserving VLAN boundaries. |
| 6 | `BrandenF_PT.pka kier_PT 4.5.1AI_Packet Tracer - Inter-VLAN Routing Challenge (1).pka` | Inter-VLAN Challenge | Integrated VLAN/trunk/routing concepts in a scenario-based challenge with end-to-end validation. |
| 7 | `BrandenF_PT.pka kier_PT 5.1.9-packet-tracer---investigate-stp-loop-prevention.pka` | STP Loop Prevention | Verified STP convergence/port roles, identified loop risks, and confirmed loop-free Layer 2 operation. |
| 8 | `BrandenF_PT.pka kier_PT 6.2.4-packet-tracer---configure-etherchannel.pka` | EtherChannel | Aggregated links for throughput and resiliency; validated logical port-channel consistency and trunk behavior. |
| 9 | `BrandenF_PT kier_PT 7.2.10-packet-tracer---configure-dhcpv4.pka` | DHCPv4 | Configured DHCP pools, gateway/DNS options, and automatic host addressing with scope verification. |
|10 | `BrandenF_PT kier_PT 7.4.1-packet-tracer---implement-dhcpv4.pka` | DHCPv4 Implementation | Implemented DHCP services in a fuller topology and validated dynamic client lease acquisition end-to-end. |
|11 | `BrandenF_PT.pka kier_PT1.4.7.pka 1.4.7AI Packet Tracer - Configure Router Interfaces.pka` | Router Interfaces | Applied interface IP addressing/no shutdown workflow and verified baseline Layer 3 reachability. |
|12 | `16.4.6 Packet Tracer - Configure Secure Passwords and SSH (1).pkz` | Device Hardening / SSH | Secured device access with encrypted credentials and remote-management hardening via SSH. |

## VLAN and Trunking Competency Summary

These labs collectively demonstrate practical switching depth beyond basic CLI syntax:

- **VLAN lifecycle skills:** planning, creation, assignment, and verification of VLAN boundaries.
- **Trunk lifecycle skills:** static trunk setup, DTP-aware negotiation control, and VLAN transport validation.
- **Inter-VLAN design choices:** implementing both **router-on-a-stick** and **Layer 3 switch SVIs** depending on topology scale.
- **Operational validation:** using pings, MAC/ARP behavior, and show-command checks to confirm forwarding outcomes.
- **Stability under growth:** integrating STP and EtherChannel so trunked VLAN environments remain loop-free and resilient.

## How to Use This Repository

1. Open any `.pka` or `.pkz` file in Cisco Packet Tracer.
2. Use each activity's instructions/assessment pane to review objectives.
3. Validate configurations from CLI (`show vlan brief`, `show interfaces trunk`, `show ip interface brief`, `show spanning-tree`, etc.).

## Audience

This repo is suitable for:

- Recruiters/hiring managers who want evidence of practical CCNA lab work.
- Instructors/mentors reviewing progression across switching/routing modules.
- Peers studying VLANs, trunking, and inter-VLAN routing implementation patterns.
