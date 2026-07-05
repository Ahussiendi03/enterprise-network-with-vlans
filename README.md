# Enterprise Network with VLANs

## Overview

This project simulates a three-floor enterprise office network using Cisco Packet Tracer.

## Features

- VLAN 10 (HR)
- VLAN 20 (IT)
- VLAN 30 (Finance)
- Router-on-a-Stick
- Inter-VLAN Routing
- Centralized DHCP Server
- DHCP Relay (ip helper-address)
- Trunk Links

## IP Addressing

| VLAN | Department | Network | Gateway |
|------|------------|---------|---------|
|10|HR|192.168.10.0/24|192.168.10.1|
|20|IT|192.168.20.0/24|192.168.20.1|
|30|Finance|192.168.30.0/24|192.168.30.1|

## Verification

- PCs receive IP addresses automatically.
- Devices in different VLANs communicate successfully.
- DHCP relay works across VLANs.

## Skills Demonstrated

- VLAN configuration
- Trunking
- Router-on-a-Stick
- DHCP
- DHCP Relay
- Inter-VLAN Routing
- Network troubleshooting
