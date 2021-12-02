# Capstone Engagement
Assessment, Analysis,  and Hardening of a Vulnerable System

## Red vs. Blue project

### Red Team `Pentester`
Penetrate a virtual machine to gain root access. Tools used in this project inlude:
  - Kali Linux
    - NMap
    - DirB (DirBuster)
    - John the Ripper
    - MSFConsole
    - MSFVenom (To create a reverse shell)
    - Meterpreter
    - File Manager
  
### Blue Team `SOC Analyst`
Using Kibana, extract logs for hard data and visualizations. Provide mitigations to harden the system in a report. Tools used in this project include:
  - Kibana
    - Packetbeat
      - The large number of requests with a very short event duration from one ip.
      - Crossreference the number of `GET` requests made to critical data.
      - Identify possible Brute Force Attack.
      - Identify suspicious files containing malicious code. 
    - Filebeat
      - Installed, but not utilized for this project.
    - Metricbeat
      - Installed, but not utilized for this project.

### Possible Recommended Mitigations Discussed:
  - Blocking the Port Scan
  - Finding the Request for the Hidden Directory
  - Preventing Brute Force Attacks
  - Detecting the WebDAV Connection
  - Identifying Reverse Shell Uploads
