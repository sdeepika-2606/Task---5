## 🔍 Task 5: Capture and Analyze Network Traffic Using Wireshark

### 🎯 Objective:

To capture live network packets using Wireshark, analyze them, identify different protocols, and gain hands-on experience in packet-level analysis.

---

### 💠 Tools Used:

* **Wireshark** (Network packet analyzer)

---

### 📦 Steps Performed:

1. **Installed Wireshark**

   * Downloaded and installed Wireshark on my system.
2. **Started Capture**

   * Selected the active network interface (Wi-Fi).
   * Started capturing live packets.
3. **Generated Traffic**

   * Visited websites such as `google.com`, `example.com`.
   * Used `ping google.com` in Command Prompt to generate ICMP packets.
4. **Stopped Capture**

   * After 1 minute, stopped the packet capture.
5. **Filtered Packets**

   * Applied filters like:

     * `http`
     * `dns`
     * `tcp`
6. **Analyzed Protocols**

   * Identified various protocols and their communication patterns.
7. **Exported Data**

   * Saved the packet capture as a `.pcap` file.

---

### 📌 Protocols Identified:

| Protocol | Purpose         | Description                                                     |
| -------- | --------------- | --------------------------------------------------------------- |
| **DNS**  | Name Resolution | Resolves domain names (e.g., google.com) to IP addresses.       |
| **HTTP** | Web Traffic     | Transfers web pages between browser and server (unencrypted).   |
| **TCP**  | Transport Layer | Ensures reliable data transmission (used by HTTP, HTTPS, etc.). |

---

### 📁 Files Included:

* `task5_capture.pcap` – Captured traffic file
* `README.md` – This report document

---



### 🤔 Key Learnings:

* Understood how different protocols work in real-time.
* Learned how to filter and inspect network packets in Wireshark.
* Gained awareness of TCP/IP and OSI layers via hands-on analysis.

