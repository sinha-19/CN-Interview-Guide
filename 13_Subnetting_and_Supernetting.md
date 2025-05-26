# 12. Subnetting & Supernetting

---

## What is Subnetting?

**Subnetting** is the process of dividing a larger network (IP address block) into smaller, more manageable sub-networks (subnets). This helps in efficient IP address utilization, improved network performance, and enhanced security.

---

### Why Subnet?

- **Efficient IP address management**
- **Improved network performance** (reduces broadcast traffic)
- **Enhanced security** (segmentation)
- **Simplifies troubleshooting**

---

## Subnet Masks

- A **subnet mask** separates the network and host portions of an IP address.
- Common subnet masks:
  - Class A: 255.0.0.0 (/8)
  - Class B: 255.255.0.0 (/16)
  - Class C: 255.255.255.0 (/24)

---

## CIDR Notation

- CIDR = Classless Inter-Domain Routing
- Expresses subnet masks as a “slash” followed by the number of network bits.
  - Example: 192.168.1.0/24 means the first 24 bits are the network part.

---

## How to Subnet

1. **Decide the number of subnets or hosts needed.**
2. **Determine the number of bits to borrow from the host portion** (to create more subnets).
3. **Calculate new subnet mask and address ranges.**
4. **Assign subnets to network segments/devices.**

---

### Example

- Given: 192.168.1.0/24, need 4 subnets.
- 2 bits needed (2² = 4 subnets).
- New mask: /26 (255.255.255.192)
- Subnet ranges:
  - 192.168.1.0/26 (hosts: .1 - .62)
  - 192.168.1.64/26 (hosts: .65 - .126)
  - 192.168.1.128/26 (hosts: .129 - .190)
  - 192.168.1.192/26 (hosts: .193 - .254)

---

## What is Supernetting?

**Supernetting** is the process of combining multiple contiguous smaller networks into a larger one. It is used mainly in route aggregation to reduce the size of routing tables.

- Also known as route summarization or aggregation.
- Allows ISPs to advertise a single summarized route for multiple networks.

---

### Example

- Combine: 192.168.0.0/24 and 192.168.1.0/24
- Supernet: 192.168.0.0/23 (covers 192.168.0.0–192.168.1.255)

---

## Common Interview Questions

1. What is subnetting and why is it used?
2. How do you calculate the number of subnets and hosts per subnet?
3. What is CIDR notation?
4. What is supernetting and its benefit?
5. Calculate the subnet mask for 8 subnets.

---

## Quick Revision Table

| Term        | Description                       |
|-------------|-----------------------------------|
| Subnetting  | Dividing a network into subnets   |
| Supernetting| Combining networks into a supernet|
| CIDR        | Flexible subnet notation          |
| Subnet Mask | Identifies network/host portions  |

---

Happy Learning! 🌐
