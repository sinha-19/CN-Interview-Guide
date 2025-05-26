# 05. Network Layer & IP Addressing

---

## What is the Network Layer?

The **Network Layer** is the third layer in the OSI model. Its main responsibility is to move packets from the source to the destination — possibly across multiple networks (routing).

---

## Main Functions of the Network Layer

- **Logical Addressing:** Assigns and manages IP addresses so devices can be uniquely identified across networks.
- **Routing:** Determines the best path for data to travel from source to destination.
- **Packet Forwarding:** Moves data packets towards their destination using routers.
- **Fragmentation & Reassembly:** Breaks large packets into smaller ones to match the network’s maximum transmission unit (MTU), and reassembles them at the destination.
- **Error Handling & Diagnostics:** Uses protocols like ICMP for reporting errors and diagnostics.

---

## Key Devices at the Network Layer

- **Routers:** Make forwarding decisions based on IP addresses.
- **Layer 3 Switches:** Operate at the network layer for fast routing within LANs.

---

## Important Protocols

| Protocol | Description               |
|----------|---------------------------|
| IP       | Internet Protocol, core protocol for logical addressing and routing |
| ICMP     | Internet Control Message Protocol, error reporting & diagnostics   |
| ARP      | Address Resolution Protocol, maps IP addresses to MAC addresses    |
| IGMP     | Internet Group Management Protocol, manages multicast groups       |

---

## IP Addressing

### What is an IP Address?

- A unique logical address assigned to each device on a network.
- **IPv4:** 32 bits, written as four decimal numbers (e.g., 192.168.1.1)
- **IPv6:** 128 bits, written as eight hexadecimal blocks (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334)

### Classes of IPv4 Addresses

| Class | Range         | Default Mask      | Purpose                    |
|-------|--------------|-------------------|----------------------------|
| A     | 1.0.0.0 - 126.255.255.255 | 255.0.0.0 | Large networks           |
| B     | 128.0.0.0 - 191.255.255.255 | 255.255.0.0 | Medium networks         |
| C     | 192.0.0.0 - 223.255.255.255 | 255.255.255.0 | Small networks         |
| D     | 224.0.0.0 - 239.255.255.255 | N/A | Multicasting              |
| E     | 240.0.0.0 - 255.255.255.255 | N/A | Research/Experimental     |

### Private vs Public IP Addresses

- **Private:** Used within local networks (e.g., 192.168.x.x)
- **Public:** Routable on the internet, assigned by ISPs

---

## Subnetting

- Divides a larger network into smaller, manageable segments (subnets).
- Helps in efficient IP address management and improves security.

---

## Routing

- **Static Routing:** Manually configured routes, suitable for small networks.
- **Dynamic Routing:** Routing tables updated automatically using protocols (e.g., RIP, OSPF, BGP).

---

## Common Interview Questions

1. What is the role of the Network Layer?
2. Explain the difference between logical and physical addressing.
3. What is the difference between IPv4 and IPv6?
4. What is subnetting and why is it used?
5. How do routers forward packets?

---

## Quick Revision Table

| Feature          | Description                        |
|------------------|------------------------------------|
| Logical Address  | IP address assigned to devices     |
| Routing          | Selecting best path for packets    |
| Fragmentation    | Breaking packets for transmission  |
| Protocols        | IP, ICMP, ARP, IGMP               |

---

Happy Learning! 🌐
