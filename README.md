# MIST Campus – A Smart Campus Cisco Project 🏫🌐

A comprehensive Cisco Packet Tracer simulation designed to modernize the **Military Institute of Science and Technology (MIST)** campus network with **IoT-driven automation**, **secure VLAN segmentation**, and **centralized digital services**.

> 🚀 Built with Cisco Packet Tracer | 🔐 VLANs & ACLs | 🌐 Web & Email Servers | 🔗 IoT Integration

---

## 📌 Overview

Traditional university networks often lack scalability, security, and smart automation. This project reimagines the MIST campus as a **Smart Campus** by implementing:

- Secure VLAN-based departmental segmentation
- IoT-powered automation (RFID access, fire detection, speaker alerts)
- Centralized Web, Email, and DNS services
- Dynamic IP management with DHCP
- RIPv2 & Static Routing for efficient inter-campus connectivity

---

## 🎯 Objectives

- 🔐 **Secure & Scalable Network Infrastructure** with 21 VLANs for departments and 2 VLANs for hostels
- 🔁 **Inter-Department Routing** using RIPv2 and static routing
- 🌐 **Smart Services** with Web, Email, and DNS servers
- 🛠️ **IoT Automation** via RFID access, fire alarms, and speaker systems
- 🔧 **Dynamic IP Allocation** using DHCP

---

## 🖥️ System Design

### VLAN Segmentation
- 21 VLANs for academic departments and administrative units
- 2 VLANs for hostel networks (Osmany Hall)

### Routing
- RIPv2 for internal router communication
- Static Routing for external services (e.g., Email server cloud)

### Security
- Access Control Lists (ACLs) to block unauthorized traffic
- Isolated VLANs to limit broadcast domains and enhance performance

### IP Management
- Router-based DHCP servers for automated IP assignments

---

## 🔗 IoT-Based Features

| Feature | Description |
|--------|-------------|
| 🔐 RFID Access | Secure, automated door access using RFID card readers |
| 🔥 Fire Monitoring | Fire detectors trigger sprinklers and alert systems |
| 📣 Piezo Speakers | Auto-announcements and emergency notifications |

---

## 🧰 Tools & Technologies

- **Simulation Tool**: Cisco Packet Tracer
- **Devices Used**:
  - 3× Cisco 2811 Routers
  - 2× Cisco 3560 Multi-Layer Switches
  - 23× Cisco 2950 Switches
  - Web, Email & DNS Servers
  - IoT modules: RFID Readers, Fire Sensors, Piezo Buzzers

---

## 📡 Network Workflow

1. PCs connect via segmented VLANs across departments and hostels
2. DHCP allocates IPs dynamically
3. Web and Email services are accessible across all VLANs
4. IoT devices automate access and alerts
5. Static routes connect internal routers to external Email server cloud

---

## 🧪 Testing & Results

- ✅ **Ping & Traceroute**: Verified connectivity across all nodes
- ✅ **Web Browsing**: Campus site accessible using domain names
- ✅ **Email Service**: Internal email exchange successful
- ✅ **IoT Systems**: RFID, Fire, and Alert devices trigger correctly

---

## 🧠 Lessons Learned

- Effective VLAN segmentation can greatly enhance both **security** and **performance**.
- IoT integration is not just futuristic — it adds real operational value in **safety** and **efficiency**.
- Role-based access and ACLs are essential in academic environments for **data integrity**.

---

## 🚀 Future Improvements

- Expand to cloud-based Learning Management Systems (LMS)
- Integrate AI for network anomaly detection
- Develop web and mobile apps for student/teacher portals
- Automate HVAC, lighting, and energy consumption tracking

---

## 🧑‍💻 Authors

👨‍🎓 Group 04 – MIST  
- Aunindya Prosad Saha (202114014)  
- G M Fahim Tazwar (202114025)  
- Md. Raiyan Buhiyan Loreen (202114052)  
- Md. Raisul Islam Rahad (202214052)

---

## 📷 Screenshots

> _Add snapshots from Packet Tracer and your PowerPoint presentation for better visual impact._

---

## 📁 Files

- `final.pkt` – Cisco Packet Tracer simulation file  
- `Networking_report.pdf` – Full project documentation  
- `Smart campus.pptx` – Presentation slides  

---

## 📚 References

- Kurose, J. F., & Ross, K. W. *Computer Networking: A Top-Down Approach*
- Smart Campus Using IoT (IJRASET 2017)
- [BDREN Smart Campus Initiative](https://www.bdren.net.bd/news/170)

---

