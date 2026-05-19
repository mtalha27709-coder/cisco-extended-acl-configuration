# 🔐 Cisco Extended ACL Configuration Lab

## 📌 Overview

This project demonstrates the configuration and implementation of **Extended Access Control Lists (ACLs)** in Cisco Packet Tracer to control and secure network traffic between multiple LANs and a server.

The lab was designed to simulate real-world network security policies where specific users are only allowed access to required services.

---

## 🖥️ Network Scenario

Two PCs are connected to different LANs through a Cisco router.

### Access Requirements

* **PC1**

  * ✅ Allowed: FTP + ICMP (Ping)
  * ❌ Blocked: HTTP & access to PC2

* **PC2**

  * ✅ Allowed: HTTP + ICMP (Ping)
  * ❌ Blocked: FTP & access to PC1

The server provides both FTP and Web services.

---

## ⚙️ What I Configured

* Extended Numbered ACL (`ACL 100`)
* Extended Named ACL (`HTTP_ONLY`)
* Interface-based ACL application
* Traffic filtering using:

  * TCP
  * ICMP
  * FTP
  * HTTP

---

## 🛠️ Technologies Used

* Cisco Packet Tracer
* Cisco IOS CLI
* Networking Fundamentals
* Access Control Lists (ACLs)

---

## ✅ Verification Performed

* Successful FTP access from PC1
* Successful HTTP access from PC2
* Successful ICMP communication
* Blocked unauthorized traffic between networks

---

## 📚 Skills Learned

* Configuring Extended ACLs
* Applying ACLs on router interfaces
* Traffic filtering and network security
* Understanding wildcard masks
* Verifying and troubleshooting ACL behavior

---

## 🚀 Learning Outcome

This lab strengthened my understanding of how network administrators use ACLs to secure networks by allowing only authorized traffic while blocking unnecessary or unauthorized access.

---

## 👨‍💻 Author

**Talha**
Cloud Cybersecurity Student | SOC & Network Security Enthusiast
