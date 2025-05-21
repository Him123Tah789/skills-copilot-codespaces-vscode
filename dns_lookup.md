## DNS Reconnaissance

**Reverse DNS Lookup**

- **Command Used:** slookup 103.40.156.214
- **Result:**  
  ** server can't find 214.156.40.103.in-addr.arpa: NXDOMAIN

**Interpretation:**  
No PTR (reverse DNS) record exists for 103.40.156.214. The IP does not resolve to a hostname. This is common and does not indicate a vulnerability.

**Next Steps:**  
Continue with forward DNS lookups or proceed to other reconnaissance steps (e.g., robots.txt, banner grabbing, directory brute-forcing).