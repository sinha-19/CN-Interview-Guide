# 04. Data Link Layer & Protocols

---

## What is the Data Link Layer?

The **Data Link Layer** is the second layer in the OSI model. It is responsible for reliable transmission of data frames between two devices on the same network segment.

---

## Main Functions of the Data Link Layer

- **Framing:** Divides data received from the Network Layer into manageable units called frames.
- **Physical Addressing:** Adds MAC (Media Access Control) addresses to frames, identifying source and destination devices on the network.
- **Error Detection & Correction:** Detects and may correct errors that occur during transmission using techniques like CRC, parity bits, etc.
- **Flow Control:** Prevents overwhelming the receiver by controlling the rate of data transmission.
- **Access Control:** Determines which device has control over the communication channel at any given time (important in shared-media networks).

---

## Sublayers of the Data Link Layer

1. **Logical Link Control (LLC):**
   - Manages communication between the Network Layer and the MAC sublayer.
   - Provides error and flow control.

2. **Media Access Control (MAC):**
   - Controls how devices gain access to the medium and permission to transmit data.
   - Handles MAC addresses.

---

## Data Link Layer Protocols

| Protocol       | Usage                         |
|----------------|------------------------------|
| Ethernet       | LAN, wired networks           |
| Wi-Fi (IEEE 802.11) | Wireless LANs           |
| PPP (Point-to-Point Protocol) | Direct links  |
| HDLC (High-Level Data Link Control) | WAN links|
| Frame Relay    | WAN, packet switching         |
| Token Ring     | LAN (legacy)                  |

---

## Error Detection Techniques

- **Parity Bit**
- **Cyclic Redundancy Check (CRC)**
- **Checksum**

---

## MAC Address

- 48-bit hardware address unique to each network interface card (NIC).
- Written in hexadecimal, e.g., `00:1A:2B:3C:4D:5E`.

---

## Common Interview Questions

1. What is the role of the Data Link Layer?
2. Explain the difference between LLC and MAC sublayers.
3. Name some protocols used at the Data Link Layer.
4. How is error detection performed at this layer?
5. What is a MAC address and why is it important?

---

## Quick Revision Table

| Function             | Description                                 |
|----------------------|---------------------------------------------|
| Framing              | Divides data into frames                    |
| Physical Addressing  | Adds source & destination MAC addresses     |
| Error Detection      | Detects/corrects errors in frames           |
| Flow/Access Control  | Manages data rate and media access          |

---

Happy Learning! 🌐
