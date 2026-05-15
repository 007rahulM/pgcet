# Computer Networks & Internet

## 🔑 What is a Computer Network?

A network is a group of computers connected to **share resources and communicate**.

---

## 📐 Types of Networks

| Type | Full Form | Coverage |
|------|-----------|---------|
| **LAN** | Local Area Network | Same building/floor |
| **MAN** | Metropolitan Area Network | City-wide |
| **WAN** | Wide Area Network | Country/world-wide |
| **PAN** | Personal Area Network | Personal devices (~10m) |

---

## 📐 OSI Model — 7 Layers (Very Frequently Asked!)

**Memory Trick: "All People Seem To Need Data Processing"**

| Layer # | Layer Name | Function | Protocols |
|---------|-----------|----------|-----------|
| 7 | **Application** | User interface | HTTP, FTP, SMTP, DNS |
| 6 | **Presentation** | Data format, encryption | SSL, JPEG, MPEG |
| 5 | **Session** | Session management | NetBIOS, RPC |
| 4 | **Transport** | End-to-end delivery, error | TCP, UDP |
| 3 | **Network** | Routing, IP addressing | IP, ICMP, RIP |
| 2 | **Data Link** | Frame delivery, MAC | Ethernet, ARP, PPP |
| 1 | **Physical** | Bits over cable/radio | Hub, Cable, Wi-Fi |

**Note:** Data travels DOWN through layers at sender, UP at receiver.

---

## 📐 TCP/IP Model — 4 Layers

| TCP/IP Layer | OSI Equivalent |
|-------------|---------------|
| Application | Application + Presentation + Session (7,6,5) |
| Transport | Transport (4) |
| Internet | Network (3) |
| Network Access | Data Link + Physical (2,1) |

---

## 📐 Important Protocols

| Protocol | Port | Purpose |
|----------|------|---------|
| **HTTP** | 80 | Web browsing |
| **HTTPS** | 443 | Secure web browsing |
| **FTP** | 21 | File Transfer |
| **SSH** | 22 | Secure remote login |
| **SMTP** | 25 | Sending email |
| **POP3** | 110 | Receiving email |
| **IMAP** | 143 | Email access |
| **DNS** | 53 | Domain name resolution |
| **DHCP** | 67/68 | Dynamic IP assignment |
| **Telnet** | 23 | Remote login (insecure) |

---

## 📐 IP Addressing

### IPv4:
- 32-bit address, written as 4 octets: **192.168.1.1**
- Range: 0.0.0.0 to 255.255.255.255

### IPv6:
- 128-bit address: **2001:0db8:85a3::8a2e:0370:7334**
- Created to solve IPv4 exhaustion

### Classes of IPv4:

| Class | Range | Use |
|-------|-------|-----|
| A | 0.0.0.0 – 127.255.255.255 | Large networks |
| B | 128.0.0.0 – 191.255.255.255 | Medium networks |
| C | 192.0.0.0 – 223.255.255.255 | Small networks |
| D | 224.0.0.0 – 239.255.255.255 | Multicast |
| E | 240.0.0.0 – 255.255.255.255 | Reserved |

### Special IPs:
- **127.0.0.1** = Loopback (localhost)
- **192.168.x.x** = Private (home/office)
- **Subnet Mask** — 255.255.255.0 (Class C) tells which part is network vs host

---

## 📐 Network Devices

| Device | Layer | Function |
|--------|-------|----------|
| **Hub** | Physical (1) | Broadcasts to all ports |
| **Switch** | Data Link (2) | Sends to specific MAC address |
| **Router** | Network (3) | Routes between networks using IP |
| **Bridge** | Data Link (2) | Connects two LAN segments |
| **Gateway** | All layers | Protocol converter |
| **Repeater** | Physical (1) | Amplifies signal |
| **Modem** | Physical (1) | Converts digital ↔ analog |

---

## 📐 Transmission Media

| Type | Examples |
|------|---------|
| **Wired** | Coaxial, Twisted Pair (Cat5/6), Fiber Optic |
| **Wireless** | Wi-Fi, Bluetooth, Infrared, Satellite |

### Speeds:
- Twisted Pair (Cat6): up to 10 Gbps
- Fiber Optic: fastest, immune to EMI

---

## 📐 Internet Terms

| Term | Meaning |
|------|---------|
| **WWW** | World Wide Web — system of web pages |
| **URL** | Uniform Resource Locator — web address |
| **DNS** | Domain Name System — converts domain to IP |
| **ISP** | Internet Service Provider |
| **Bandwidth** | Data transfer capacity (bps) |
| **Latency** | Delay in data transmission |
| **Firewall** | Security barrier filtering traffic |
| **VPN** | Virtual Private Network — encrypted tunnel |
| **Cookie** | Small data stored by browser |
| **Cache** | Locally stored web content for speed |

---

## ⚡ Quick Memory Table

| Remember | Detail |
|---------|--------|
| OSI layers | 7 = Application (top), 1 = Physical (bottom) |
| TCP = reliable | Acknowledges received data |
| UDP = fast | No acknowledgement (used for streaming) |
| Router works at | Layer 3 (Network) |
| Switch works at | Layer 2 (Data Link) |
| HTTP = port 80 | HTTPS = port 443 |

---

## 📝 Practice Problems

1. How many layers are in the OSI model?
   (A) 4  (B) 5  (C) 6  (D) 7

2. Which device operates at the Network layer?
   (A) Hub  (B) Switch  (C) Router  (D) Repeater

3. TCP ensures:
   (A) Fast transmission  (B) Reliable, ordered delivery  
   (C) Multicast only  (D) Wireless only

4. DNS is used for:
   (A) Encrypting data  (B) Domain to IP translation  
   (C) File transfer  (D) Email sending

5. Port number for HTTPS is:
   (A) 80  (B) 21  (C) 443  (D) 25

6. IPv4 address is how many bits?
   (A) 16  (B) 32  (C) 64  (D) 128

7. Which OSI layer is responsible for routing?
   (A) Transport  (B) Network  (C) Data Link  (D) Physical

8. LAN covers which area?
   (A) City  (B) Country  (C) Building/floor  (D) World

---


> 📖 **[See detailed step-by-step solutions →](./07-Computer-Networks-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q32](../papers-qp/2025/Questions.md#q32)
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q7](../papers-qp/2023/Questions.md#q7), [Q59](../papers-qp/2023/Questions.md#q59)

> Links open the exact question in the respective year's paper for cross-reference.
