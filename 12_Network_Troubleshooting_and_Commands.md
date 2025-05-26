# 12. Network Troubleshooting & Commands

---

## Why is Network Troubleshooting Important?

Network troubleshooting is the process of identifying, diagnosing, and resolving problems in a network to ensure smooth and efficient communication between devices.

---

## Common Troubleshooting Steps

1. **Identify the Problem:** Gather information about symptoms (slow speed, no connectivity, etc.).
2. **Establish a Theory:** Consider possible causes (hardware, configuration, ISP issues, etc.).
3. **Test the Theory:** Use tools and commands to check network status.
4. **Establish an Action Plan:** Decide how to fix the issue.
5. **Implement the Solution:** Apply fixes (replace cables, change configs, etc.).
6. **Verify Full System Functionality:** Make sure the problem is resolved.
7. **Document the Solution:** Keep records for future reference.

---

## Essential Network Commands

| Command      | Description                                 | Example Usage            |
|--------------|---------------------------------------------|--------------------------|
| `ping`       | Tests connectivity to a host                 | ping google.com          |
| `tracert`/`traceroute` | Shows path to a host               | tracert 8.8.8.8          |
| `ipconfig` (Windows) | Displays IP config                   | ipconfig                 |
| `ifconfig` (Linux/macOS) | Shows network interfaces         | ifconfig                 |
| `nslookup`   | Queries DNS info for a domain                | nslookup github.com      |
| `netstat`    | Displays network connections & ports         | netstat -an              |
| `arp`        | Shows & modifies ARP cache                   | arp -a                   |
| `route`      | Displays/modifies routing table              | route print              |
| `nmap`       | Scans for open ports/devices                 | nmap 192.168.1.1         |
| `telnet`     | Tests connectivity to a specific port        | telnet smtp.gmail.com 25 |

---

## Common Issues and Solutions

| Issue                    | Possible Causes              | Solution                        |
|--------------------------|-----------------------------|----------------------------------|
| No Internet              | Cable unplugged, ISP down   | Check cables, restart modem      |
| Slow Network             | Bandwidth hog, interference | Limit usage, change Wi-Fi channel|
| IP Conflict              | Duplicate IPs assigned      | Set static IPs, check DHCP       |
| DNS Not Resolving        | Wrong DNS config            | Change to public DNS (8.8.8.8)   |
| Can’t Connect to Device  | Firewall, wrong IP/subnet   | Check firewall, verify IP config |

---

## Basic Troubleshooting Flowchart

1. **Check Physical Layer:** Cables, LEDs, power.
2. **Check IP Configuration:** Use `ipconfig`/`ifconfig`.
3. **Check Connectivity:** Use `ping`.
4. **Check Routing:** `traceroute`/`tracert`.
5. **Check DNS:** Use `nslookup`.
6. **Check for Open Ports:** Use `netstat`, `nmap`.

---

## Common Interview Questions

1. How do you troubleshoot network connectivity issues?
2. What does the `ping` command do?
3. How can you find out which ports are open on your machine?
4. What would you do if a website is not resolving?
5. Explain the steps of basic network troubleshooting.

---

## Quick Revision Table

| Command    | Function                  |
|------------|---------------------------|
| ping       | Test connectivity         |
| traceroute | Show path to host         |
| ipconfig   | View IP configuration     |
| nslookup   | Resolve DNS               |
| netstat    | View open ports           |

---

Happy Learning! 🌐
