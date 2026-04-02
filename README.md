# WAZUH SIEM-LAB

I used Wazuh, a free, open source platform that is used for threat prevention, detection, and response to build a SIEM lab with a Linux server and a Windows endpoint. The Linux and Windows VMs were ran on VirtualBox.

I simulated brute-force login attempts on the Windows endpoint and created custom rules to detect batches of repeated failed logins and other suspicious activity such as suspicious permission elevations. The Windows VM sends the logs, Wazuh analyzes them, and alerts are then generated and shown in the dashboard as seen below.


<img width="2525" height="1016" alt="image" src="https://github.com/user-attachments/assets/af5c6a51-3c6d-4006-8d21-0106e4b61855" />
