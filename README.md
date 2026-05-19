# THM-Sighunt
Creation of detection rules through Sigma based on intel of a new threat.

# Scenario
You are hired as a Detection Engineer for your organization. During your first week, a ransomware incident has just concluded, and the Incident Responders of your organization have successfully mitigated the threat. With their collective effort, the Incident Response (IR) Team provided the IOCs based on their investigation. Your task is to create Sigma rules to improve the detection capabilities of your organization and prevent future incidents similar to this.

## Indicators of Compromise
### Execution of a malicious HTA payload from a phishing link.
### Execution of the Certutil tool to download the Netcat binary.
### Netcat execution to establish a reverse shell.
### Enumeration of privilege escalation vectors through PowerUp.ps1.
### Abused service modification privileges to achieve System privileges.
### Collected sensitive data by archiving via 7-zip.
### Exfiltrated sensitive data through cURL binary.
### Executed ransomware with huntme as the file extension. 
