# Python-Project
**A simple Python-based project of the network scanner with a GUI represented by Tkinter. This utility is powered by the Scapy library for doing network scanning: ICMP ping to identify host availability and scan common TCP (22, 23, 80, 443, 8080) and UDP (53, 67, 68, 123) ports. It provides a friendly interface to input the host address to be scanned, and it shows its results in a text area that is scrollable. This project looks to show a simple working example of network scanning and GUI creation in Python.**

**Frameworks, Technologies, and Libraries Used:**
* Python: The programming language used to develop the project.
* Tkinter: A standard Python library used for creating graphical user interfaces (GUIs).
* Scapy: A Python library used for packet manipulation and network scanning.

**Features:**
* ICMP Ping: Checks if a host is up by sending an ICMP echo request.
* TCP Port Scan: Scans a predefined list of TCP ports (22, 23, 80, 443, 8080) and identifies open ports.
* UDP Port Scan: Scans a predefined list of UDP ports (53, 67, 68, 123) and identifies open ports.
* GUI: Provides a user-friendly interface to input the host address and display scan results.

**How It Works:**
* The user inputs a host address in the GUI.
* The tool performs an ICMP ping to check if the host is reachable.
* It scans for open TCP and UDP ports from predefined lists.
* The results of the scans are displayed in the GUI.
