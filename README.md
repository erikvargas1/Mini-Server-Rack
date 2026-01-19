## DeskPi-Server-Rack

![hehey](https://github.com/user-attachments/assets/0d29696a-23eb-469e-9982-7706e584b287)

## Design Philosophy

My mindset behind choosing this equipment was based on a few core principles:
- Mini form factor – Everything must physically fit in a 10” server rack
- Low power usage – Efficient CPUs and components suitable for 24/7 operation
- Low heat & noise – No screaming fans or excessive cooling requirements
- Real-world relevance – Hardware and software that reflect enterprise concepts

----

## Tools & Technologies

- **Pi-hole** enables network-wide DNS filtering to block ads and trackers, improving privacy and performance for all devices without client-side software.
- **OPNsense** is an open-source firewall and routing platform providing stateful packet inspection, NAT, VLAN routing, and advanced security services.
- **Proxmox** is a Type-1 hypervisor built on Debian that supports both KVM virtual machines and LXC containers.
- **Ubiquiti UniFi** provides centrally managed networking hardware, including switches and wireless access points. I use it for reliable performance, clean network visibility, and simplified management across my entire home lab.

----

## Server Rack Equipment

> Compute nodes

Lenovo ThinkCentre M920q | Intel Core i5-8500T | 16GB RAM | 500GB NVMe SSD
- PCIe x16 Riser Card
- iPolex Dual-Port Gigabit NIC Intel I350-AM2 Controller PCIe 2.1 x4

HP EliteDesk 800 G4 | Intel Core i5-8500T | 16GB RAM | 250GB NVMe SSD

----

> Switching & Wireless

- Ubiquiti UniFi Switch Lite 8-Port Gigabit Switch with 4 PoE+
- Ubiquiti U6+ Wireless Access Point Dual-band Wi-Fi 6 (802.11ax)

---

> Server Rack

- GeeekPi 8U Server Cabinet, 10 inch Server Rack
- GeeekPi 12 Port Patch Panel, 10inch 0.5U CAT6 Network Patch Panel
- GeeekPi 1U Server Rack Shelf

-----




