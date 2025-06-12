# 🔐 SecuBiz – Secure Network Simulation for Small Business

This project simulates a **cost-effective, secure multi-branch network** for a fictional small business called **SecuBiz**. Developed using **Cisco Packet Tracer v8.1.0.0722**, it demonstrates best practices in VLAN segmentation, ACL enforcement, static routing, VPN simulation, and wireless security.

> 📁 All project files are included in the uploaded `SecuBiz.7z` archive.

---

## 🧠 Project Overview

**Objective:** To build a secure and scalable network for a small business environment using only accessible, free tools and academic principles.

The network solution includes:

- 🔹 Department-based VLAN segmentation
- 🔹 Inter-VLAN routing using router-on-a-stick
- 🔹 Access Control Lists (ACLs) to restrict interdepartmental traffic
- 🔹 Static routing for main office ↔ remote branch connectivity
- 🔹 GRE tunnel simulation for VPN traffic
- 🔹 WPA2-PSK wireless security
- 🔹 ACL-based firewall simulation
- 🔹 Centralized servers (DNS, FTP, Mail)

---

## 🧰 Tools & Technologies Used

- **Cisco Packet Tracer** (v8.1.0.0722)
- Cisco 2811 Routers & 2960 Switches
- CLI-based Configuration (Switches/Routers)
- VLAN, ACL, GRE Tunneling, Static Routing
- WPA2 Wireless Access Configuration

---

## 📁 Repository Contents

| File / Folder           | Description                                   |
|-------------------------|-----------------------------------------------|
| `SecuBiz.7z`            | Full project archive: Packet Tracer file, screenshots, test logs, report |
| `README.md`             | Project overview and structure                |

---

## 📸 Key Configuration Screenshots (in archive)

- VLAN setup and verification
- ACL creation and test pings
- GRE tunnel configuration between routers
- Wireless security setup (WPA2)
- Inter-site routing tests
- Firewall-style access controls via ACLs

---

## ✅ Functional Demonstrations

- ICMP ping tests between VLANs (permitted and denied)
- ACL testing logs confirming access restrictions
- Tunnel reachability between main site and remote branch
- Server VLAN access validation
- Wireless device access and encryption

---

## 💡 Future Improvements

- Full IPsec VPN implementation (beyond Packet Tracer capabilities)
- Dynamic routing (OSPF/EIGRP) for scalability
- Centralized authentication (RADIUS/AAA server)
- Dedicated firewall appliance simulation

---

## 📄 Notes

This project was developed as part of a final-year academic submission focused on applied network security in constrained environments. It reflects real-world small business concerns such as simplicity, budget, and layered security.

---

## 🧠 Acknowledgements

- Cisco Networking Academy (Packet Tracer tool and documentation)


---

## 📜 License

This repository is intended for **educational and portfolio demonstration purposes** only.  
Reproduction for commercial use is not permitted without prior consent.
