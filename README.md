# Python Port Scanner

A lightweight Python tool that scans for open TCP ports 
on a target host. Built as part of a cybersecurity 
learning portfolio to demonstrate basic network 
reconnaissance concepts.

## Features
- Detects open ports within a specified range
- Resolves hostnames to IP addresses
- Displays scan timestamp and open port summary

## Requirements
- Python 3.x
- No external libraries required

## Usage
```bash
python port_scanner.py
```
Enter the target IP or hostname, start port, 
and end port when prompted.

## Example Output
```
Scanning target: 192.168.1.1
Time started: 2025-11-01 14:23:01

[OPEN] Port 22
[OPEN] Port 80
[OPEN] Port 443

Scan complete. 3 open ports found.
```

## Disclaimer
This tool is for educational purposes only.
Only use on systems you own or have explicit 
permission to test. Unauthorised scanning is illegal.

## Author
Jin Hyuck Kim
github.com/[yourusername]
