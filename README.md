This README describes the steps followed to capture and analyze network traffic for protocol identification.

#### **Tools Used**

* **Wireshark** – For packet capture and analysis

#### **Steps Followed**

1. **Install Wireshark**
   Download from [https://www.wireshark.org/](https://www.wireshark.org/) and install it.

2. **Start Packet Capture**
   Open Wireshark and select your active network interface (e.g., Wi-Fi). Click the blue shark fin icon to begin capture.

3. **Generate Traffic**
   Browse websites or ping a server to create network activity. Let the capture run for about 1 minute.

4. **Stop the Capture**
   Click the red square stop icon. Save the file as `wifi1.pcapng`.

5. **Filter and Identify Protocols**
   Use Wireshark’s filter (e.g., `arp`, `quic`, `icmpv6`, `dns`) to identify protocols in use.

6. **Analyze Packets**
   Review packet details for protocol behavior, source/destination, and message types.

7. **Generate the Report**
   A structured `.docx` report was generated summarizing the findings.

---

#### **Output Files**

* `wifi1.pcapng`: Original packet capture file
