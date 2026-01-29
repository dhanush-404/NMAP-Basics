# Task 9 – Network Scanning using NMAP(Network Mapper)

## Tool
- Nmap

## Target
- IP: 10.197.12.102  
- Device: My own Kali NetHunter (Android)

## Command
      nmap -sV -O --script vuln 10.197.12.102 -oN network_scan.txt

## Result
- Device detected as Android (Linux kernel)
- Open ports: 8008, 8009, 8443, 9000
- No major vulnerabilities found
- Every screenshots of the command execution and scan-report.txt is attached

## Note
Scan performed on my own device for educational purposes only.
