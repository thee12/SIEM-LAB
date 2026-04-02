# WAZUH SIEM-LAB

I used Wazuh, a free, open source platform that is used for threat prevention, detection, and response to build a SIEM lab with a Linux server and a Windows endpoint. The Linux and Windows VMs were ran on VirtualBox.

I simulated brute-force login attempts on the Windows endpoint and created custom rules to detect batches of repeated failed logins and other suspicious activity such as suspicious permission elevations. The Windows VM sends the logs, Wazuh analyzes them, and alerts are then generated and shown in the dashboard as seen below.

<img width="2525" height="226" alt="image" src="https://github.com/user-attachments/assets/e8d345ab-66d4-400c-b2cc-3cd2b1f76b40" />


<img width="2525" height="1016" alt="image" src="https://github.com/user-attachments/assets/af5c6a51-3c6d-4006-8d21-0106e4b61855" />

<img width="2559" height="1112" alt="image" src="https://github.com/user-attachments/assets/f0d6ddb0-2ca1-4ec9-922d-8df22e84bd06" />

<img width="2558" height="1031" alt="image" src="https://github.com/user-attachments/assets/ebd2244d-6c3e-4c35-98d9-1dca9dac674d" />

