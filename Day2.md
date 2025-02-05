# **Types of Networks and Network Components (Level-wise)**

## **1. Types of Networks (Based on Scale)**

| **Type**         | **Description** | **Example** |
|-----------------|---------------|-------------|
| **PAN (Personal Area Network)** | Small network for personal use, typically within a few meters. | Bluetooth devices, Smartwatches, Wireless earphones. |
| **LAN (Local Area Network)** | Covers a small area like a home, office, or building. | Office Wi-Fi, Home networks, Ethernet-based networks. |
| **WLAN (Wireless LAN)** | LAN that uses wireless connections instead of wired. | Wi-Fi in cafes, homes, offices. |
| **MAN (Metropolitan Area Network)** | Covers a city or large campus. | Cable TV networks, University networks. |
| **WAN (Wide Area Network)** | Covers a large geographical area, connecting multiple LANs. | The Internet, Corporate networks connecting global offices. |
| **CAN (Campus Area Network)** | Interconnects multiple LANs within a campus (like universities, military bases). | University or hospital networks. |
| **SAN (Storage Area Network)** | A dedicated network for data storage. | Enterprise storage systems, Data center storage. |
| **VPN (Virtual Private Network)** | A secure, encrypted connection over a public network. | Remote work connections, Secure internet browsing. |

---

## **2. Network Components (Layer-wise in OSI Model)**  
Each network component operates at a specific level of the OSI model.

### **Physical Layer (Layer 1) - Hardware Transmission**
- **Cables** (Ethernet, Fiber optic, Coaxial)  
- **Repeaters** (Boosts signal over long distances)  
- **Hubs** (Broadcasts data to all devices in a network)  

### **Data Link Layer (Layer 2) - MAC & Switching**
- **Switches** (Smart devices that forward data based on MAC addresses)  
- **Bridges** (Connects two LAN segments)  
- **Network Interface Cards (NICs)** (Physical adapters for network access)  

### **Network Layer (Layer 3) - Routing & Addressing**
- **Routers** (Directs data packets based on IP addresses)  
- **Layer 3 Switches** (Combines switch and routing functionalities)  
- **Gateways** (Connects different network types and protocols)  

### **Transport Layer (Layer 4) - End-to-End Communication**
- **Firewalls** (Filters and secures network traffic)  
- **Load Balancers** (Distributes network traffic evenly)  

### **Session Layer (Layer 5) - Managing Sessions**
- **Session Managers** (Manages connections between applications)  

### **Presentation Layer (Layer 6) - Data Format & Encryption**
- **Encryption Devices** (SSL/TLS encryption for secure communication)  

### **Application Layer (Layer 7) - End-User Communication**
- **Web Browsers** (HTTP, HTTPS, FTP clients)  
- **Email Servers** (SMTP, IMAP, POP3 handling)  

---

## **3. Network Components (Based on Network Hierarchy)**

| **Level** | **Component** | **Function** |
|-----------|--------------|--------------|
| **Core Level** | Core Routers, High-speed Switches | High-capacity backbone connecting different networks. |
| **Distribution Level** | Layer 3 Switches, Firewalls | Aggregates traffic, enforces security policies. |
| **Access Level** | Ethernet Switches, Wireless Access Points | Provides direct connectivity to end-users. |

---

# **IP Address and MAC Address: Overview & Types**  

## **1. IP Address (Internet Protocol Address)**
An **IP address** is a unique numerical identifier assigned to devices on a network, allowing them to communicate over the internet or a local network.  

### **Types of IP Addresses**  
#### **A. Based on Version:**  
- **IPv4 (Internet Protocol Version 4)**  
  - 32-bit address (e.g., `192.168.1.1`)  
  - Supports ~4.3 billion unique addresses  
- **IPv6 (Internet Protocol Version 6)**  
  - 128-bit address (e.g., `2001:0db8:85a3::8a2e:0370:7334`)  
  - Supports a virtually unlimited number of addresses  

#### **B. Based on Usage:**  
- **Public IP Address** (Globally unique, assigned by ISPs)  
- **Private IP Address** (Used within local networks, e.g., `192.168.1.1`, `10.0.0.1`)  
- **Static IP Address** (Manually assigned, does not change)  
- **Dynamic IP Address** (Assigned by DHCP, changes periodically)  

---

## **2. MAC Address (Media Access Control Address)**
A **MAC address** is a unique identifier assigned to a network interface card (NIC) of a device. It operates at **Layer 2 (Data Link Layer)** of the OSI model.

### **MAC Address Types:**
- **Unicast MAC Address** (Identifies a single device)  
- **Multicast MAC Address** (Used to send data to multiple devices)  
- **Broadcast MAC Address** (`FF:FF:FF:FF:FF:FF` - sends data to all devices on a network)  

---

## **Key Differences:**
| **Feature**  | **IP Address**  | **MAC Address**  |
|-------------|---------------|---------------|
| **Purpose**  | Identifies a device on a network for communication | Uniquely identifies a device’s network interface  |
| **Layer**  | Network Layer (Layer 3) | Data Link Layer (Layer 2)  |
| **Format**  | IPv4 (32-bit), IPv6 (128-bit) | 48-bit (e.g., `00:1A:2B:3C:4D:5E`)  |
| **Changeability**  | Can be changed (dynamic/static) | Usually fixed (but can be spoofed) |
| **Scope**  | Works across networks (global) | Works within local networks (LAN) |

---
