\# Port Scan Risk Analysis



\## Target

192.168.1.241



\## Scan Type

Nmap SYN Scan with Service Detection



Command Used:

nmap -sS -sV 192.168.1.241



---



\## Findings



\### Open Ports



Document the ports discovered in the scan.



Example:



Port 80 - HTTP  

Risk: Unencrypted traffic may expose credentials.



Port 443 - HTTPS  

Risk: Low risk if TLS is configured correctly.



---



\## Recommendations



• Disable unnecessary services  

• Ensure encrypted protocols are used  

• Regularly monitor open ports

