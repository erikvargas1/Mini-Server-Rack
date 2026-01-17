## DeskPi-Server-Rack

![homerack](https://github.com/user-attachments/assets/f59f7bee-c839-48b2-ba6a-872ffb86c3ae)

----


## Design Philosophy

My mindset behind choosing this equipment was based on a few core principles:
- Mini form factor – Everything must physically fit in a 10” server rack
- Low power usage – Efficient CPUs and components suitable for 24/7 operation
- Low heat & noise – No screaming fans or excessive cooling requirements
- Real-world relevance – Hardware and software that reflect enterprise concepts

----

## Tools & Technologies
- PiHole for DNS filterning
- 



----

## Server Rack Equipment

**Compute nodes** 

Lenovo ThinkCentre M920q | Intel Core i5-8500T | 16GB RAM | 500GB NVMe SSD
- PCIe x16 Riser Card
- iPolex Dual-Port Gigabit NIC Intel I350-AM2 Controller PCIe 2.1 x4

HP EliteDesk 800 G4 | Intel Core i5-8500T | 16GB RAM | 250GB NVMe SSD

----

**Switching & Wireless**
- Ubiquiti UniFi Switch Lite 8-Port Gigabit Switch with 4 PoE+
- Ubiquiti U6+ Wireless Access Point Dual-band Wi-Fi 6 (802.11ax)

---

**Server Rack**
- GeeekPi 8U Server Cabinet, 10 inch Server Rack
- GeeekPi 12 Port Patch Panel, 10inch 0.5U CAT6 Network Patch Panel
- GeeekPi 1U Server Rack Shelf

-----




## Objectives


## Project Breakdown 




-----

### Why I choose OPNSense over pfSense 

<img width="200" height="120" alt="image" src="https://github.com/user-attachments/assets/bb120692-af67-4ea4-a1e7-a1ad4be3bcfe" />


OPNSense boasts quite the roaster of features3, most relevant among those for me were the following:
- 802.1Q VLAN support and Stateful Firewalls: Which would allow me to reproduce the network segregation I had previously implemented for my IoT devices.
- VPN support: Both as a server and a client with support for IPSec, OpenVPN, and Wireguard.
- Intrusion detection and prevention systems.
- A comprehensive catalog of plugins.
- Simple configuration backup & restore mechanism.
- Weekly security updates with a twice-a-year releasing strategy.

All of these features are made even more accessible thanks to a very elegant UI which also enables easy reporting and monitoring. Finally, the project boasts and exhaustive online documentation and rich community which would make future debugging hopefully not too much of a headache.


-------




