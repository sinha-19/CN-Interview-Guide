# 07. Transport Layer: TCP & UDP

---

## What is the Transport Layer?

The **Transport Layer** is the fourth layer in the OSI model. It is responsible for providing reliable and efficient data transfer between end systems (hosts).

---

## Main Functions of the Transport Layer

- **Segmentation and Reassembly:** Breaks large messages into smaller segments for transmission and reassembles them at the destination.
- **End-to-End Communication:** Provides logical communication between application processes running on different hosts.
- **Flow Control:** Ensures that the sender does not overwhelm the receiver with too much data at once.
- **Error Control:** Detects and retransmits lost or corrupted segments.
- **Multiplexing/Demultiplexing:** Allows multiple applications to use the network simultaneously by using port numbers.

---

## Key Protocols: TCP & UDP

### TCP (Transmission Control Protocol)

- **Connection-oriented:** Establishes a connection before data transfer.
- **Reliable:** Ensures data is delivered in order and without errors.
- **Flow and Congestion Control:** Manages data rate for efficient transmission.
- **Examples:** Web browsing (HTTP/HTTPS), email (SMTP), file transfer (FTP).

### UDP (User Datagram Protocol)

- **Connectionless:** No need to establish a connection before sending data.
- **Unreliable:** No guarantee of delivery, order, or error checking.
- **Lightweight and Fast:** Used when speed is more important than reliability.
- **Examples:** Streaming, online gaming, DNS queries, VoIP.

---

## TCP vs UDP

| Feature         | TCP                                | UDP                           |
|-----------------|------------------------------------|-------------------------------|
| Connection      | Connection-oriented                | Connectionless                |
| Reliability     | Reliable, error-checked, ordered   | Unreliable, no order checking |
| Speed           | Slower (overhead for reliability)  | Faster (low overhead)         |
| Use Cases       | HTTP, FTP, SMTP, SSH               | DNS, VoIP, Streaming, Gaming  |
| Flow Control    | Yes                                | No                            |
| Congestion Ctrl | Yes                                | No                            |

---

## Ports & Sockets

- **Port Number:** A 16-bit number used to identify specific applications/services (e.g., HTTP uses port 80).
- **Socket:** Combination of IP address and port number (e.g., 192.168.1.10:80).

---

## Error and Flow Control Methods

- **Acknowledgments (ACKs)**
- **Timers and Retransmission**
- **Sliding Window Protocol**

---

## Common Interview Questions

1. What are the main responsibilities of the transport layer?
2. Compare TCP and UDP.
3. What is a socket?
4. How does TCP ensure reliable delivery?
5. Give examples of applications that use TCP and UDP.

---

## Quick Revision Table

| Protocol | Connection | Reliability | Use Case         |
|----------|------------|-------------|------------------|
| TCP      | Yes        | Yes         | Web, Email, FTP  |
| UDP      | No         | No          | Streaming, DNS   |

---

Happy Learning! 🌐
