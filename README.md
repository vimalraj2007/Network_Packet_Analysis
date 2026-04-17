# 📡 Wireshark Traffic Analysis 

## 📌 About
Captured and analyzed network traffic using Wireshark to identify protocols and understand communication behavior.

---
## 🛠️ Tools
- Wireshark

---
## 🔍 Filters Used
- dns
- http
- icmp
- tcp.flags.syn == 1
- ip.addr == <local-ip>
- !(dns || http || tcp || udp)
- http.request.method == "POST"

---
## 📊 Protocols Identified
- DNS
- HTTP
- ICMP
- TCP

---
## 🔍 Key Findings
- DNS resolves domain names
- TCP establishes connections
- HTTP traffic is visible (not secure)
- ICMP used for connectivity
- No suspicious traffic detected
---

## 📁 Repository Structure

```
Network_Packet_Analysis/
├── Screenshots/
├── Networks_Analysis.pcapng
├── README.md
└── Report.pdf
```
---

## 🛡️ Conclusion

- Wireshark helps monitor and analyze network traffic to understand communication and detect issues.
----
## 👤 Author
Vimal Raj R
