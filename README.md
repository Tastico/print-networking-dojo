# Print Networking Dojo

Interactive networking trainer for print and IT field engineers. One HTML file, zero dependencies,
works offline. Open `interactive-dojo.html` in any browser and it runs.

## Why this exists

Field engineers get handed printers and MFPs and are expected to debug IP conflicts, firewalls, DNS,
and raw socket printing on the spot. Most networking courses are written for datacenter people. This
one is written for the person standing in front of a machine with a laptop and a cable tester.

## Modules (18)

1. IP Addressing and Subnets
2. Ports
3. TCP vs UDP
4. SSL/TLS and Certificates
5. RAW 9100 and LPR
6. SNMP and CPCA
7. SMB and Scan-to-Folder
8. Firewalls, VLANs and Proxies
9. DNS, DHCP and NAT
10. Device Agents and Deployment
11. Printer Languages
12. Printer Drivers
13. Print Management
14. Troubleshooting Methodology
15. Physical Connectivity and Cabling
16. Authentication and Access Control
17. Mobile Printing and Cloud
18. Security Hardening

## Features

- A lesson and a graded quiz per module (every answer must be right to pass, retries allowed)
- 13 on-site scenarios with a hint and an answer
- Port match drill
- XP, levels and awards, progress saved in the browser
- Works on a phone; light and dark themes
- No server, no install, no internet needed

## How it is built

Version 5 is generated from a content-as-data engine: lessons, quizzes and scenarios are data files,
and one build step produces this single HTML file. The same engine also runs as a served, multi-user
dojo with server-side grading and a team progress view. That edition adds field cases built from real
(anonymised) service jobs and a vendor glossary, which stay out of this public file.

## License

MIT. Use it, fork it, teach a class with it.
