# 02. OSI & TCP/IP Models

---

## What Are Network Models?

Network models are conceptual frameworks that standardize the functions of a communication system, enabling different devices and systems to communicate seamlessly.

---

## OSI Model (Open Systems Interconnection)

The **OSI Model** is a 7-layer conceptual model that standardizes network communication functions into seven distinct layers.

### The 7 Layers of OSI

| Layer | Number | Key Functions | Example Protocols |
|-------|--------|---------------|-------------------|
| Application      | 7 | User interface, network services | HTTP, FTP, SMTP |
| Presentation     | 6 | Data translation, encryption, compression | SSL, JPEG |
| Session          | 5 | Dialog control, synchronization | NetBIOS, RPC |
| Transport        | 4 | Reliable data transfer, error recovery | TCP, UDP |
| Network          | 3 | Logical addressing, routing | IP, ICMP |
| Data Link        | 2 | Framing, MAC addressing, error detection | Ethernet, PPP |
| Physical         | 1 | Transmission of raw bits over media | Cables, Hubs |

---

## Mnemonics to Remember OSI Layers

- **Top Down:** All People Seem To Need Data Processing
- **Bottom Up:** Please Do Not Throw Sausage Pizza Away

---

## TCP/IP Model

The **TCP/IP Model** (Internet Protocol Suite) is a 4-layer model used practically for designing the Internet.

| TCP/IP Layer      | Corresponding OSI Layers | Protocols/Examples      |
|-------------------|-------------------------|-------------------------|
| Application       | 7, 6, 5                 | HTTP, FTP, SMTP, DNS    |
| Transport         | 4                       | TCP, UDP                |
| Internet          | 3                       | IP, ICMP, ARP           |
| Network Access    | 2, 1                    | Ethernet, Wi-Fi         |

---

## Comparison: OSI vs TCP/IP

| Aspect        | OSI Model         | TCP/IP Model     |
|---------------|-------------------|------------------|
| Layers        | 7                 | 4                |
| Development   | Theoretical       | Practical/Implemented |
| Protocols     | General           | Standardized     |
| Usage         | Academics/Teaching| Real-world/Internet |

---

## Real-World Analogy

Imagine sending a letter:
- Each OSI layer adds its own "envelope" (header), like putting your letter in an envelope, putting it in a bag, loading it onto a truck, etc., until it reaches the receiver.

---

## Common Interview Questions

1. What are the seven layers of the OSI model?
2. Explain the function of each OSI layer.
3. How does the OSI model differ from the TCP/IP model?
4. Which protocols operate at the Transport layer?
5. Why do we use layered network models?

---

## Quick Revision Table

| OSI Layer | Function              | Example Protocol |
|-----------|-----------------------|------------------|
| 7         | Application           | HTTP, FTP        |
| 6         | Presentation          | SSL, JPEG        |
| 5         | Session               | NetBIOS, RPC     |
| 4         | Transport             | TCP, UDP         |
| 3         | Network               | IP, ICMP         |
| 2         | Data Link             | Ethernet, PPP    |
| 1         | Physical              | Cables, Hubs     |

---

Happy Learning! 🌐
