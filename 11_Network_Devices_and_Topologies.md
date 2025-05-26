# 11. Network Devices & Topologies

---

## Common Network Devices

| Device      | Function                                        | OSI Layer      |
|-------------|-------------------------------------------------|----------------|
| Hub         | Broadcasts data to all devices in a LAN         | Physical (1)   |
| Switch      | Forwards data to specific device based on MAC    | Data Link (2)  |
| Bridge      | Divides a network into segments                  | Data Link (2)  |
| Router      | Routes data between different networks           | Network (3)    |
| Gateway     | Connects networks with different protocols       | All Layers     |
| Modem       | Modulates and demodulates digital/analog signals | Physical (1)   |
| Access Point| Connects wireless devices to wired network       | Data Link (2)  |
| Repeater    | Amplifies/extends network signals                | Physical (1)   |
| Firewall    | Filters traffic for security                     | Varies         |

---

## Device Roles

- **Hub:** Simple device, no intelligence, sends data everywhere (used less now).
- **Switch:** Smarter, sends data only to the intended device (based on MAC address).
- **Router:** Connects different networks/LANs, works with IP addresses.
- **Access Point:** Provides wireless connectivity (Wi-Fi).
- **Firewall:** Protects networks by filtering traffic.

---

## Network Topologies

**Topology** is the arrangement/layout of network devices and cables.

### Types of Topologies

| Topology    | Description                            | Pros                           | Cons                        |
|-------------|----------------------------------------|--------------------------------|-----------------------------|
| Bus         | All devices share a single cable        | Easy to install, cheap         | Collisions, not scalable    |
| Star        | All devices connect to a central hub    | Easy to manage, isolatable     | Hub failure = network down  |
| Ring        | Devices form a closed loop              | Predictable performance        | One failure = network down  |
| Mesh        | Devices interconnected (full/partial)   | High reliability, redundancy   | Expensive, complex          |
| Tree        | Hierarchical, combines bus & star       | Scalable, easy to manage       | Cable length, complexity    |
| Hybrid      | Mix of two or more topologies           | Flexible, scalable             | Complex design              |

---

## Visual Representations

- **Bus:** Device --- Device --- Device (single line)
- **Star:**      Hub/Switch
                 /   |   \
             Device Device Device
- **Ring:** Device -- Device -- Device -- (loops back to first)
- **Mesh:** All devices connected to each other

---

## Choosing a Topology

- **Bus:** Small, temporary networks.
- **Star:** Most common for modern LANs.
- **Ring:** Used in some legacy systems.
- **Mesh:** Backbone networks, critical systems.
- **Tree/Hybrid:** Large, complex organizations.

---

## Common Interview Questions

1. What is the difference between a hub, switch, and router?
2. Explain different network topologies and their advantages.
3. Which topology is most reliable?
4. Why is mesh topology rarely used in small networks?
5. What role does a firewall play in a network?

---

## Quick Revision Table

| Device    | Layer    | Key Function             |
|-----------|----------|-------------------------|
| Hub       | 1        | Broadcasts data         |
| Switch    | 2        | Forwards to MAC address |
| Router    | 3        | Routes between networks |
| AP        | 2        | Wireless connection     |
| Firewall  | Varies   | Security                |

---

Happy Learning! 🌐
