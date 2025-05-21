## Service Discovery (Nmap)

**Command Used:**
```bash
nmap -sV -Pn -p 9999 103.40.156.214
```

**Results:**
- Host is up.
- Port 9999/tcp is open.
- Service: http
- Server: Apache httpd 2.4.62 (Debian)

**Interpretation:**  
The target is running an Apache HTTP server (version 2.4.62) on Debian, listening on TCP port 9999. This information can be used to look up public vulnerabilities (CVEs) affecting this version of Apache or Debian configuration.

**Next Steps:**  
- Check for known vulnerabilities in Apache httpd 2.4.62.
- Enumerate web application content and test for weaknesses.
- Perform vulnerability scanning and manual testing against the web application.
