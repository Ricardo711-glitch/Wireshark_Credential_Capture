# Wireshark_Credential_Capture
Lab notes and analysis from a credential capture experiment using Wireshark
# Wireshark Credential Capture

## Overview
This lab simulates credential interception using Wireshark to analyze insecure network traffic.

## Tools Used
- Wireshark
- Kali Linux
- DVWA (Damn Vulnerable Web App)

## Objective
Capture credentials sent over the network and analyze how plaintext login information can be exposed.

## Steps Performed
1. Set up DVWA on localhost.
2. Logged in using weak credentials (`admin:password123`) on a vulnerable page.
3. Captured traffic using Wireshark.
4. Applied HTTP filters and followed the TCP stream to reveal plaintext credentials.

## Findings
- Usernames and passwords sent over HTTP can be easily intercepted.
- Wireshark makes it simple to inspect unencrypted traffic.

## Lessons Learned
- HTTPS is critical for secure communications.
- Network monitoring can help detect potential leaks and threats.
