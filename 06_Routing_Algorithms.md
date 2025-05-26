# 06. Routing Algorithms

---

## What are Routing Algorithms?

**Routing algorithms** determine the optimal path for data packets to travel from source to destination across interconnected networks.

---

## Key Functions of Routing

- **Path Selection:** Find the best route for data.
- **Forwarding:** Move packets from one network to another.
- **Network Discovery:** Learn about network topology and available paths.
- **Error Handling:** Detect and reroute around failed links or devices.

---

## Types of Routing

- **Static Routing:** Routing tables are manually configured and do not change unless updated by an administrator.
- **Dynamic Routing:** Routing tables are updated automatically using routing protocols.

---

## Classification of Routing Algorithms

### 1. Distance Vector Routing

- Each router shares its routing table with immediate neighbors.
- Uses algorithms like **Bellman-Ford**.
- Slow convergence, susceptible to routing loops.
- Example Protocols: **RIP (Routing Information Protocol)**

### 2. Link State Routing

- Routers share information about directly connected links with all routers in the network.
- Builds a complete map of the network.
- Faster convergence, less prone to loops.
- Uses **Dijkstra’s Algorithm**.
- Example Protocols: **OSPF (Open Shortest Path First), IS-IS**

### 3. Path Vector Routing

- Used in inter-domain routing (between autonomous systems).
- Maintains the path information that gets updated as routes move through the network.
- Example Protocol: **BGP (Border Gateway Protocol)**

---

## Routing Table

- Data structure maintained by routers.
- Stores information about network destinations and the best paths to reach them.

---

## Routing Metrics

- **Hop Count:** Number of routers a packet must pass through.
- **Bandwidth:** Data carrying capacity of a link.
- **Delay:** Time taken for a packet to reach the destination.
- **Cost:** Arbitrary value assigned by the admin or protocol.

---

## Routing Protocols Overview

| Protocol | Type           | Description                      |
|----------|----------------|----------------------------------|
| RIP      | Distance Vector| Simple, used in small networks   |
| OSPF     | Link State     | Scalable, used in large networks |
| BGP      | Path Vector    | Internet backbone, inter-domain  |
| EIGRP    | Hybrid         | Cisco proprietary, combines features |

---

## Common Interview Questions

1. What is the difference between static and dynamic routing?
2. Explain distance vector vs link state routing.
3. What is a routing table?
4. Name common routing protocols and their features.
5. How does OSPF differ from RIP?

---

## Quick Revision Table

| Algorithm Type | Example Protocol | Key Feature      |
|----------------|------------------|------------------|
| Distance Vector| RIP              | Simplicity       |
| Link State     | OSPF             | Fast convergence |
| Path Vector    | BGP              | Inter-domain     |

---

Happy Learning! 🌐
