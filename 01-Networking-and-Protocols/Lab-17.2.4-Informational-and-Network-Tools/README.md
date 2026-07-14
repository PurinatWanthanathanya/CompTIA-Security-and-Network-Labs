# Lab 17.2.4: Informational and Network Tools

**Role:** Network Administrator

## 🎯 Objective
To utilize command-line diagnostic tools to analyze network routing paths and determine the number of hops required to reach a target destination.

## 🚀 Execution Steps
1. **Network Path Tracing (Traceroute):** 
   * Utilized the `traceroute` (or `tracert` on Windows) command in the terminal to map the exact path data packets take from the local machine to reach a specific external domain or remote IP address.
2. **Hop Analysis & Troubleshooting:** 
   * Monitored the command output to count the number of intermediate routers (hops) between the source and the destination. 
   * Analyzed the response times (in milliseconds) for each hop to identify potential network bottlenecks, latency spikes, or routing failures.

## 📊 Results & Evidence
* Successfully mapped the complete network route to the target server, identified the total number of hops, and verified that there were no dropped connections along the path.

> 📸 traceroute ip address<img width="940" height="513" alt="image" src="https://github.com/user-attachments/assets/7d4a9832-fefc-4c95-8e1b-8d95a43ea401" />

## 🧠 Key Takeaways
* **Traceroute vs. Ping:** Learned a critical distinction in troubleshooting. While `ping` only tells you *if* a destination is reachable, `traceroute` tells you *exactly where* the connection drops by revealing every router the packet passes through.
* **Understanding TTL (Time-To-Live):** Discovered the underlying mechanism of the tool. Traceroute works by intentionally sending packets with incrementally increasing Time-To-Live (TTL) values, forcing each router along the path to send back an ICMP error message, which maps the route.
* **Latency Identification:** Understood how to read the latency columns (response times) in the output. A sudden spike in milliseconds at a specific hop clearly indicates which router or ISP is experiencing heavy traffic or issues.
