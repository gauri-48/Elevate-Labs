# Elevate-Labs
Internship
Local Network Open Ports Scanning Internship Task
Overview
As part of my cybersecurity internship, I completed a foundational network security assessment—scanning the local network for open ports using Nmap and (optionally) Wireshark. This exercise helped me understand network exposure and introduced me to common reconnaissance tools used by both admins and attackers.

Objective
The main goal was to discover open ports on devices in my local network, identify associated services, and evaluate potential security risks. This task provided hands-on experience with network enumeration and vulnerability assessment.

Tools Used
Nmap: Industry-standard port scanning tool (free)

Wireshark: Optional packet analysis tool

Steps Undertaken
Nmap Installation: I downloaded Nmap from the official website and set it up on my Linux machine.

Network Range Identification: Using ifconfig/ip a, I determined my subnet (e.g., 192.168.1.0/24).

Performing TCP SYN Scan: Ran the following command to begin scanning:

text
nmap -sS 192.168.1.0/24
This executed a SYN scan across all devices on the subnet.

Results Analysis: Recorded the list of active IPs and their open ports. For each port, I noted the associated service (e.g., SSH, HTTP, SMB).

Packet Capture with Wireshark: For deeper analysis, I optionally used Wireshark to inspect traffic during a scan, which provided insight into how port scans manifest at the packet level.

Research & Risk Identification: I researched common services running on discovered open ports and identified possible vulnerabilities (e.g., outdated SMB, open telnet).

Reporting: Saved scan results and compiled findings into a readable format (text/HTML), including screenshots for documentation.

Experience & Learnings
This practical task reinforced my understanding of core network concepts, including the behavior of TCP scans and how open ports may pose potential risks. By correlating Nmap data with Wireshark captures, I learned how scanning activity is reflected in raw network traffic—knowledge crucial for both offensive and defensive security roles.

I also realized the importance of regularly monitoring local networks for exposed services, as even basic scans can highlight unexpected risk areas. Delving into the specifics of discovered ports improved my research skills regarding common vulnerabilities and helped build an analytical mindset for future pentesting tasks.

Key Takeaways
Gained proficiency in Nmap scanning techniques and interpreting results.

Understood real-world implications of open ports for network security.

Improved my workflow for documenting and reporting technical findings.

Enhanced my ability to identify and research service-specific risks.

Screenshots & Documentation
See attached screenshot for evidence of task completion.
