## **Tools Used in the OSCP Cheatsheet**

### **Network & Port Scanning**
- **nmap** - Port scanning and service enumeration
- **nbtscan** - NetBIOS scanning

### **DNS Enumeration**
- **host** - DNS query tool
- **dnsrecon** - DNS reconnaissance
- **dnsenum** - DNS enumeration via brute-force
- **nslookup** - DNS lookup tool

### **SMB/File Sharing**
- **crackmapexec** / **nxc** (NetExec) - SMB enumeration and credential testing
- **enum4linux** - SMB/SNMP enumeration
- **smbclient** - SMB client for file access
- **smbmap** - SMB share mapping and enumeration
- **impacket-psexec** - Remote command execution via SMB
- **impacket-smbserver** - SMB server for file transfers

### **FTP**
- **ftp** - FTP client
- **wget** - File download (FTP capable)
- **hydra** - Brute-force authentication

### **SMTP**
- **netcat (nc)** - Network communication
- **smtp-user-enum** - SMTP user enumeration
- **swaks** - SMTP testing tool

### **SNMP**
- **snmpcheck** - SNMP information gathering
- **onesixtyone** - SNMP community string brute-force
- **snmpwalk** - SNMP MIB tree walk
- **snmpbulkwalk** - SNMP bulk data retrieval

### **Remote Access**
- **xfreerdp** - RDP client for Windows remote access
- **ssh** - Secure shell access

### **File Transfer & HTTP**
- **python3 http.server** - HTTP server for file serving
- **wget** - File download tool
- **curl** - URL-based file transfer
- **certutil** - Windows file download utility
- **iwr** (Invoke-WebRequest) - PowerShell download

### **Reverse Shells & Handlers**
- **Metasploit (msfconsole)** - Multi/handler for reverse shell management
- **netcat (nc)** - Reverse shell listener and command execution
- **penelope** - Shell stabilization and upgrade tool

### **Privilege Escalation - Windows**
- **PowerUp.ps1** - Windows privilege escalation enumeration
- **winPEASx64.exe** - Windows privilege escalation automation
- **SigmaPotato** - Token impersonation exploit
- **RoguePotato** - Potato family exploit
- **GodPotato** - Token impersonation
- **JuicyPotatoNG** - Token impersonation variant
- **SharpEfsPotato** - EFS privilege escalation
- **PrintSpoofer** - Printer spooler exploitation

### **Privilege Escalation - Linux**
- **linpeas.sh** - Linux privilege escalation enumeration
- **unix-privesc-check** - Unix privilege escalation checker

### **Exploitation & Payload Generation**
- **msfvenom** - Metasploit payload generation (implied)
- **x86_64-w64-mingw32-gcc** - Windows DLL/executable compilation

### **Post-Exploitation & Enumeration**
- **Get-ChildItem** (PowerShell) - File system search
- **Get-Process** (PowerShell) - Process enumeration
- **systeminfo** - System information
- **whoami** - Current user/group information
- **icacls** - NTFS permissions enumeration
- **Get-CimInstance** (PowerShell) - WMI queries
- **Services.msc** - Windows Services GUI
- **schtasks** - Scheduled task enumeration
- **procmon** - Process Monitor for DLL tracking
- **Event Viewer** - Windows event log analysis

### **Git Tools**
- **git** - Version control commands (status, log, show)

### **Compilation & Development**
- **mingw32-gcc** - Cross-compiler for Windows executables
