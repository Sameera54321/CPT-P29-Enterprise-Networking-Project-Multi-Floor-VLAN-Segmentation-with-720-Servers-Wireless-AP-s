# Cisco-Packet-Tracer-project-29

I’m thrilled to share my latest and most comprehensive networking project – Enterprise Networking Project 03 – a full‑scale campus network simulation built in Cisco Packet Tracer.The design spans two floors and six VLANs (Management, Research, HR, Marketing, Accounting, Finance), each with its own PC, wireless access point, and printer.

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-29/blob/main/23.jpg?raw=true)

## 📌 Summary

### Enterprise Networking Project 03 is a Cisco Packet Tracer simulation of a multi‑department corporate campus. The topology includes:

    2 floors (First Floor & Second Floor)

    6 VLANs – 10 (Management), 20 (Research), 30 (HR), 40 (Marketing), 50 (Accounting), 60 (Finance)

    Per VLAN: PC, Access Point, Printer

    Server farm – over 720 servers (Server0 … Server719+)

    Interconnecting switches, routers, and multilayer switches (implied)

### The project demonstrates:

    VLAN creation and port assignment for wired/wireless clients

    Wireless LAN configuration – SSIDs, radio settings, security (WPA2)

    Inter‑VLAN routing – router‑on‑a‑stick or Layer 3 switch with SVIs

    DHCP services – automatic IP assignment for all clients (from the server farm)

    Printer sharing – each VLAN has a dedicated network printer

    Large‑scale server farm – addressing, service configuration (HTTP, FTP, DNS, email), and scalability testing

## ✨ Features

    ✅ 6 VLANs (10,20,30,40,50,60) – complete departmental isolation

    ✅ 2 floors – realistic building topology

    ✅ Wireless access points – one per VLAN (6+ APs)

    ✅ Printers – one per VLAN for shared printing

    ✅ PCs – one per VLAN (expandable)

    ✅ 720+ servers – massive data centre for enterprise services

    ✅ Inter‑VLAN routing – communication between departments

    ✅ Full Packet Tracer file (.pkt) – ready to open and explore

    ✅ Documentation – VLAN mapping, IP addressing plan, wireless configs, server list

### VLAN & IP Plan :

| VLAN | Department | Subnet | Gateway | DHCP Range |
| :--- | :--- | :--- | :--- | :--- |
| 10 | Management | 192.168.10.0/24 | 192.168.10.1 | 192.168.10.10 – 254 |
| 20 | Research | 192.168.20.0/24 | 192.168.20.1 | 192.168.20.10 – 254 |
| 30 | HR | 192.168.30.0/24 | 192.168.30.1 | 192.168.30.10 – 254 |
| 40 | Marketing | 192.168.40.0/24 | 192.168.40.1 | 192.168.40.10 – 254 |
| 50 | Accounting | 192.168.50.0/24 | 192.168.50.1 | 192.168.50.10 – 254 |
| 60 | Finance | 192.168.60.0/24 | 192.168.60.1 | 192.168.60.10 – 254 |
| (Servers) | Data Centre | 10.10.0.0/22 | 10.10.0.1 | 10.10.0.10 – 10.10.3.254 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router, switch, access point, and server configurations

    (Optional) Python – for generating server configurations (720+ servers)

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more floors or VLANs.

    Implement dynamic routing (OSPF/EIGRP) between multiple routers.

    Configure redundant links and STP enhancements.

    Add a firewall (ASA) for perimeter security.

    Introduce VoIP phones for each department.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
