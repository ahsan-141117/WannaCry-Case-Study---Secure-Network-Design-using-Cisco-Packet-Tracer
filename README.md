# 🙌 Please credit Mohammad Ahsan Hummayoun when using, sharing, or adapting this work

---

# 🔐 Secure Enterprise Network Design – Ransomware Mitigation (WannaCry Case Study)

## 📌 Overview
This project presents a secure enterprise network architecture designed to mitigate ransomware attacks, using **WannaCry** as a case study. The network was built and tested in **Cisco Packet Tracer**, focusing on reducing attack surface and preventing lateral movement in a typical mid-sized organization.

---

## 🎯 Objectives
- Analyze WannaCry using the **Cyber Kill Chain** and **MITRE ATT&CK**
- Identify weaknesses in a flat network architecture  
- Design and implement a **segmented, secure network**  
- Apply **defense-in-depth** principles to stop ransomware propagation  

---

## ⚙️ Key Features
- **Network Segmentation:** Multi-VLAN design (department-based isolation)  
- **Access Control:** ACLs for traffic filtering and service restriction  
- **Dynamic Routing:** OSPF between multilayer switch and edge router  
- **IP Management:** DHCP pools with automated addressing  
- **Layer 2 Security:** Port Security & DHCP Snooping  
- **Threat Containment:** Quarantine VLAN for infected hosts  
- **Resilience:** Backup FTP server for data recovery  
- **Attack Mitigation:** DNS Kill-Switch to disrupt WannaCry execution  

---

## 🛡️ Security Improvements
The redesigned network eliminates flat topology risks by:
- Restricting **lateral movement**
- Blocking vulnerable services (SMB/NetBIOS)
- Introducing **segmentation + traffic control**
- Enabling early-stage disruption of the attack lifecycle  

---

## 🧰 Technologies Used
- Cisco Packet Tracer  
- VLANs & Inter-VLAN Routing  
- OSPF (Dynamic Routing)  
- Access Control Lists (ACLs)  
- DHCP & DHCP Snooping  
- Port Security  

---

## 🚀 Key Takeaway
Even simple network-level controls like segmentation and filtering can **break the cyber kill chain early**, preventing large-scale ransomware impact.
