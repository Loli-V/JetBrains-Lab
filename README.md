# JetBrains-Lab

Forensics in cybersecurity is finding, collecting and analysing evidence of a cyber attack.
In this lab, investigated a breach determining the entry point, type of attack, extent of the compromise and exit of the attacker.

## Skills Learned
- Network/Digital Forensics
- Log Analysis
- Incidence Response
- IOC Identification
- Threat Analysis

## Tools
- CyberDefenders
- WireShark

## Task
**Scenario:** During a recent security incident, an attacker successfully exploited a vulnerability in our web server, allowing them to upload webshells and gain full control over the system. The attacker utilized the compromised web server as a launch point for further malicious activities, including data manipulation. 
As part of the investigation, You are provided with a packet capture (PCAP) of the network traffic during the attack to piece together the attack timeline and identify the methods used by the attacker. The goal is to determine the initial entry point, the attacker's tools and techniques, and the compromise's extent.

Q1. Identifying the attacker's IP address helps trace the source and stop further attacks. What is the attacker's IP address?

<img width="1331" height="650" alt="Screenshot 2026-07-30 072748" src="https://github.com/user-attachments/assets/aa6d6283-e4a9-4cac-9160-dd6c23790623" />


Q2. To identify potential vulnerability exploitation, what version of our web server service is running?

<img width="1355" height="638" alt="Screenshot 2026-07-30 101648" src="https://github.com/user-attachments/assets/51b5bd0c-7ac4-4598-89de-3a05af19abde" />


Q3. After identifying the version of our web server service, what CVE number corresponds to the vulnerability the attacker exploited?

<img width="1364" height="644" alt="Screenshot 2026-07-30 102222" src="https://github.com/user-attachments/assets/6d3f417d-ffc0-405a-856e-c49e648a8b2b" />


Q4. The attacker exploited the vulnerability to create a user account. What credentials did he set up?

<img width="1351" height="628" alt="Screenshot 2026-07-30 103043" src="https://github.com/user-attachments/assets/9126d686-d9bc-4663-916e-1940a3b63987" />


Q5. The attacker uploaded a webshell to ensure his access to the system. What is the name of the file that the attacker uploaded?

<img width="1336" height="619" alt="Screenshot 2026-07-30 104721" src="https://github.com/user-attachments/assets/fdd9bb88-0f6d-46a8-8231-d8f2747d2c38" />


Q6. When did the attacker execute their first command via the web shell?

<img width="1351" height="628" alt="Screenshot 2026-07-30 103043" src="https://github.com/user-attachments/assets/8d6c1f4a-653b-4458-a27e-1a7501079e17" />


Q7. The attacker tampered with a text file that contained the credentials of the admin user of the webserver. What new username and password did the attacker write in the file?

<img width="1361" height="630" alt="Screenshot 2026-07-30 104828" src="https://github.com/user-attachments/assets/fa688739-4dfc-4dea-9a8f-ae73c31f15d7" />


Q8. What is the MITRE Technique ID for the attacker's action in the previous question (Q7) when tampering with the text file?

<img width="1358" height="630" alt="Screenshot 2026-07-30 134708" src="https://github.com/user-attachments/assets/d0509e5e-301f-4308-bae8-cd7978297bbe" />


Q9. The attacker tried to escape from the container, but he didn’t succeed, what is the command that he used for that?

<img width="1350" height="621" alt="Screenshot 2026-07-30 105457" src="https://github.com/user-attachments/assets/54b8b589-ae81-497d-b2fe-599cabad86b0" />
