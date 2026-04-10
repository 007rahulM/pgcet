# Computer Networks — Practice Problem Solutions

---

### Q1

**❓ Question:** How many layers are in the OSI model?
(A) 4  (B) 5  (C) 6  (D) 7

**🤔 What I understood:** This is asking me to recall the exact number of layers in the OSI (Open Systems Interconnection) reference model.

**💡 What I'll use:** My knowledge of the OSI model from this chapter.

**✏️ My Thought Process:**
- Option A — 4: **Wrong** — 4 layers describes the **TCP/IP model** (or Internet model), not OSI.
- Option B — 5: **Wrong** — Not a standard count for any major model.
- Option C — 6: **Wrong** — OSI has 7 layers, not 6.
- Option D — 7: **Correct** — The OSI model has exactly **7 layers** (bottom to top):
  1. Physical, 2. Data Link, 3. Network, 4. Transport, 5. Session, 6. Presentation, 7. Application.
  Mnemonic: **"Please Do Not Throw Sausage Pizza Away"**

**✅ Answer: (D) 7**

---

### Q2

**❓ Question:** Which device operates at the Network layer?
(A) Hub  (B) Switch  (C) Router  (D) Repeater

**🤔 What I understood:** This is asking me to identify which networking device functions at OSI Layer 3 (Network layer).

**💡 What I'll use:** My knowledge of network devices and their OSI layers from this chapter.

**✏️ My Thought Process:**
- Option A — Hub: **Wrong** — A hub operates at **Layer 1 (Physical)**. It simply broadcasts incoming signals to all ports with no intelligence.
- Option B — Switch: **Wrong** — A switch operates at **Layer 2 (Data Link)**. It forwards frames based on MAC addresses within a local network.
- Option C — Router: **Correct** — A router operates at **Layer 3 (Network)**. It routes packets between different networks using IP addresses. Routers read IP headers to determine the best path for packet forwarding.
- Option D — Repeater: **Wrong** — A repeater operates at **Layer 1 (Physical)**. It amplifies/regenerates signals to extend cable distance.

**✅ Answer: (C) Router**

---

### Q3

**❓ Question:** TCP ensures:
(A) Fast transmission  (B) Reliable, ordered delivery  (C) Multicast only  (D) Wireless only

**🤔 What I understood:** This is asking me to identify the key characteristic that TCP (Transmission Control Protocol) guarantees.

**💡 What I'll use:** My knowledge of TCP vs. UDP from this chapter.

**✏️ My Thought Process:**
- Option A — Fast transmission: **Wrong** — **UDP** prioritizes speed over reliability (used for video streaming, gaming). TCP prioritizes reliability, which adds overhead (handshaking, acknowledgments) and is slower.
- Option B — Reliable, ordered delivery: **Correct** — TCP is a **connection-oriented** protocol that guarantees: (1) all packets are delivered (retransmits lost ones), (2) packets arrive in the correct order, and (3) there are no duplicates. Used for HTTP, email, file transfers where data integrity is critical.
- Option C — Multicast only: **Wrong** — TCP is a unicast protocol (point-to-point). Multicast is typically handled by UDP-based protocols.
- Option D — Wireless only: **Wrong** — TCP works over any network medium — wired, wireless, fiber, etc.

**✅ Answer: (B) Reliable, ordered delivery**

---

### Q4

**❓ Question:** DNS is used for:
(A) Encrypting data  (B) Domain to IP translation  (C) File transfer  (D) Email sending

**🤔 What I understood:** This is asking me to identify the function of DNS (Domain Name System).

**💡 What I'll use:** My knowledge of DNS and internet protocols from this chapter.

**✏️ My Thought Process:**
- Option A — Encrypting data: **Wrong** — Encryption is handled by protocols like TLS/SSL (used in HTTPS). DNS itself doesn't encrypt data.
- Option B — Domain to IP translation: **Correct** — DNS is like the internet's phone book. It translates human-readable domain names (like `www.google.com`) into machine-readable IP addresses (like `142.250.195.100`) so computers can locate servers.
- Option C — File transfer: **Wrong** — File transfer is handled by **FTP** (File Transfer Protocol) or SFTP, not DNS.
- Option D — Email sending: **Wrong** — Email is sent using **SMTP** (Simple Mail Transfer Protocol). DNS does play a supporting role (finding mail server addresses via MX records), but DNS itself is not for email sending.

**✅ Answer: (B) Domain to IP translation**

---

### Q5

**❓ Question:** Port number for HTTPS is:
(A) 80  (B) 21  (C) 443  (D) 25

**🤔 What I understood:** This is asking me to recall the well-known port number assigned to HTTPS.

**💡 What I'll use:** My knowledge of standard port numbers from this chapter.

**✏️ My Thought Process:**
- Option A — 80: **Wrong** — Port 80 is used by **HTTP** (unencrypted web traffic).
- Option B — 21: **Wrong** — Port 21 is used by **FTP** (File Transfer Protocol) for command/control.
- Option C — 443: **Correct** — Port **443** is the standard port for **HTTPS** (HTTP Secure — HTTP over TLS/SSL). All encrypted web browsing uses this port.
- Option D — 25: **Wrong** — Port 25 is used by **SMTP** (email sending protocol).

**Key port numbers to remember:** HTTP=80, HTTPS=443, FTP=21, SMTP=25, DNS=53, SSH=22

**✅ Answer: (C) 443**

---

### Q6

**❓ Question:** IPv4 address is how many bits?
(A) 16  (B) 32  (C) 64  (D) 128

**🤔 What I understood:** This is asking me to recall the bit-length of an IPv4 address.

**💡 What I'll use:** My knowledge of IP addressing from this chapter.

**✏️ My Thought Process:**
- Option A — 16 bits: **Wrong** — 16 bits would give only 65,536 addresses — far too few for the internet.
- Option B — 32 bits: **Correct** — IPv4 uses **32-bit** addresses, written as 4 groups of 8 bits (octets) in dotted-decimal notation: e.g., `192.168.1.1`. This gives 2³² ≈ 4.3 billion unique addresses.
- Option C — 64 bits: **Wrong** — Not a standard IP address length.
- Option D — 128 bits: **Wrong** — **IPv6** uses 128-bit addresses (to solve IPv4 address exhaustion), but this question asks about IPv4.

**✅ Answer: (B) 32**

---

### Q7

**❓ Question:** Which OSI layer is responsible for routing?
(A) Transport  (B) Network  (C) Data Link  (D) Physical

**🤔 What I understood:** This is asking me to identify which OSI layer handles the routing of packets between different networks.

**💡 What I'll use:** My knowledge of OSI layer responsibilities from this chapter.

**✏️ My Thought Process:**
- Option A — Transport (Layer 4): **Wrong** — Transport layer handles end-to-end communication, flow control, and error checking (TCP/UDP). Not routing.
- Option B — Network (Layer 3): **Correct** — The **Network layer** is responsible for **routing** — determining the best path for packets to travel from source to destination across multiple networks, using logical addresses (IP addresses). Routers operate here.
- Option C — Data Link (Layer 2): **Wrong** — Data Link handles node-to-node delivery within a single network segment using MAC addresses. Switches operate here.
- Option D — Physical (Layer 1): **Wrong** — Physical layer deals with raw bit transmission over physical media (cables, signals). No routing logic here.

**✅ Answer: (B) Network**

---

### Q8

**❓ Question:** LAN covers which area?
(A) City  (B) Country  (C) Building/floor  (D) World

**🤔 What I understood:** This is asking me to identify the geographical coverage of a LAN (Local Area Network).

**💡 What I'll use:** My knowledge of network types and their coverage areas from this chapter.

**✏️ My Thought Process:**
- Option A — City: **Wrong** — A city-wide network is a **MAN** (Metropolitan Area Network).
- Option B — Country: **Wrong** — A country-wide or continent-wide network is a **WAN** (Wide Area Network). The internet is the largest WAN.
- Option C — Building/floor: **Correct** — A **LAN** covers a limited area like a single building, floor, office, or campus. Examples: your home Wi-Fi, a company's office network, a school computer lab.
- Option D — World: **Wrong** — A worldwide network is the **internet** (a global WAN).

**Network coverage order: LAN (room/building) < MAN (city) < WAN (country/world)**

**✅ Answer: (C) Building/floor**

---

[← Back to Practice Problems](./07-Computer-Networks.md)
