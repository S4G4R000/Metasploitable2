# Metasploitable2
Here, I've uploaded a basic walkthrough on Enumeration steps for a vulnerable Metasploitable2 server.

## Introduction

This report documents my penetration testing conducted on the Metasploitable2 vulnerable machine. I targeted the IP address `192.168.1.78` for scanning and enumeration.

### Scanning with Nmap

I utilized Nmap, a network scanning tool, to scan the target system for open ports and services.

### Enumeration with SMBClient

I conducted enumeration on port `445` using SMBClient to gather information about available shares and workgroups.

### Anonymous Login Success

I successfully achieved anonymous login in the `/tmp` and `/IPC$` shares of the `WORKGROUP/root` directory.

## Conclusion

My penetration testing on the Metasploitable2 vulnerable machine revealed several vulnerabilities, including successful anonymous login and access to sensitive directories. These findings underscore the importance of securing network shares and implementing proper access controls to mitigate potential security risks.

