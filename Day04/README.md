
## Networking Concepts

### 1. Network
A **network** is a group of interconnected devices that can communicate and share resources (like files, printers, or internet).

---

### 2. Subnet
A **subnet** (short for sub-network) divides a large network into smaller, more manageable segments.  
- Helps improve performance and security.  
- Example: A company network may be split into subnets for HR, Finance, and IT departments.

---

### 3. IP Address
An **IP address** (Internet Protocol address) is a unique identifier assigned to each device on a network.  
- Used to route data between devices over the internet or local network.

#### Types of IP Addresses:

| Feature            | IPv4                          | IPv6                                  |
|--------------------|-------------------------------|----------------------------------------|
| Address Length     | 32-bit                        | 128-bit                                |
| Format             | Decimal (e.g., 192.168.0.1)   | Hexadecimal (e.g., 2001:0db8::1)       |
| Usage              | Most widely used              | Slowly replacing IPv4                  |
| Header Complexity  | Simple                        | More complex                           |


---

### 4. MAC Address
A **MAC address** (Media Access Control) is a hardware address assigned to a device’s network interface card (NIC).  
- Unique to each device.  
- Format: `00:1A:2B:3C:4D:5E`

---

## TCP vs UDP

| Protocol | TCP                          | UDP                         |
|----------|------------------------------|-----------------------------|
| Full Form | Transmission Control Protocol | User Datagram Protocol     |
| Connection | Connection-oriented          | Connectionless             |
| Speed | Slower (more reliable)         | Faster (less reliable)     |
| Use Cases | Web, Email, File Transfer   | Video streaming, Gaming    |
| Reliability | Ensures delivery            | No delivery guarantee      |

---

## Cyber Attack Timeline

Here’s a typical sequence of a targeted cyber attack:

1. **Malicious Email** is sent to an employee.
2. Employee **opens the email**.
3. Reads **content** with a **suspicious attachment** (often password-protected).
4. Employee **unzips** the file.
5. Extracts the content and **runs the executable (.exe)** file.
6. The executable uploads and executes a **PowerShell script**.
7. The script attempts to **bypass UAC (User Account Control)**.
8. Attacker gains access to the system.

---

## Reconnaissance (Recon)

Reconnaissance is the **information gathering phase** before launching a cyberattack.

### Types of Recon:
- **Passive Recon** – Collecting data without interacting with the target (e.g., using public sources).
- **Active Recon** – Directly interacting with the target system (e.g., port scanning).

---


## Tools to Explore

- [Have I Been Pwned](https://haveibeenpwned.com)  
  - Check if your email or account was involved in a data breach.
  
- [Wayback Machine](https://archive.org/web)  
  - View archived versions of websites for research or digital forensics.

---

