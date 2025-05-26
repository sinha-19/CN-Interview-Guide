# 15. Best Practices & Interview Q&A

---

## Network Design Best Practices

- **Use Subnetting:** Efficiently segment networks for performance and security.
- **Implement VLANs:** Separate network traffic logically.
- **Redundancy:** Use redundant links/devices to avoid single points of failure.
- **Document Networks:** Keep updated diagrams and IP address plans.
- **Use Secure Protocols:** Prefer SSH, HTTPS, SFTP over insecure alternatives.
- **Regular Backups:** Backup configurations and important data frequently.
- **Update Firmware/Software:** Patch network devices regularly.
- **Strong Passwords & MFA:** Use complex passwords and enable multi-factor authentication.
- **Monitor Networks:** Use monitoring tools (SNMP, NetFlow, Syslog) for proactive alerts.

---

## Troubleshooting Best Practices

- **Start with Layer 1:** Always check cables, LEDs, and physical connections first.
- **Use Standard Commands:** Familiarize with commands like ping, traceroute, ipconfig, nslookup.
- **Check Logs:** Review device/system logs for clues.
- **Divide and Conquer:** Isolate problems by segment.
- **Document Issues:** Keep track of problems and solutions for future reference.

---

## Security Best Practices

- **Firewalls & ACLs:** Define clear access rules.
- **Network Segmentation:** Isolate sensitive data/devices.
- **Encryption:** Encrypt sensitive traffic.
- **User Education:** Train users on phishing and safe practices.
- **Regular Audits:** Assess vulnerabilities and compliance routinely.

---

## Common Networking Interview Q&A

### 1. What is the OSI Model? Name its layers.
- The OSI Model is a conceptual framework for networking. Layers: Physical, Data Link, Network, Transport, Session, Presentation, Application.

### 2. Difference between TCP and UDP?
- TCP is connection-oriented and reliable; UDP is connectionless and faster but unreliable.

### 3. What is a subnet mask? Why is it important?
- A subnet mask separates the network and host portions of an IP address; enables subnetting.

### 4. How does NAT (Network Address Translation) work?
- NAT translates private IPs to a public IP for internet access, conserving public addresses.

### 5. What is DHCP? Its purpose?
- DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses to devices.

### 6. What is VLAN and why is it used?
- VLAN (Virtual LAN) logically segments a network for better performance and security.

### 7. Explain three-way handshake in TCP.
- SYN (client) → SYN-ACK (server) → ACK (client): establishes a reliable connection.

### 8. Difference between switch and router?
- Switch operates at Layer 2, connects devices within a LAN; Router operates at Layer 3, connects different networks.

### 9. What is ARP?
- Address Resolution Protocol maps IP addresses to MAC addresses.

### 10. How do you troubleshoot a network issue?
- Check physical connections, use diagnostic commands, check configuration, isolate the problem.

---

## Quick Revision

| Topic       | Key Point                       |
|-------------|---------------------------------|
| Subnetting  | Efficient IP management         |
| VLAN        | Logical segmentation            |
| NAT         | Private to public IP translation|
| DHCP        | Auto IP assignment              |
| TCP/UDP     | Reliable vs fast communication  |

---

Good luck for your interviews! 🚀
