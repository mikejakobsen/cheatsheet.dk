---
title: NMap
category: Hacking
---

|COMMAND                                                                        |DESCRIPTION                                                                                                                           |
|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
|nmap -v -sS -A -T4 target                                                      |Nmap verbose scan runs syn stealth T4 timing (should be ok on LAN) OS and service version info traceroute and scripts against services|
|nmap -v -sS -p–A -T4 target                                                    |As above but scans all TCP ports (takes a lot longer)                                                                                 |
|nmap -v -sU -sS -p- -A -T4 target                                              |As above but scans all TCP ports and UDP scan (takes even longer)                                                                     |
|nmap -v -p 445 –script=smb-check-vulns –script-args=unsafe=1 192.168.1.X       |Nmap script to scan for vulnerable SMB servers – WARNING: unsafe=1 may cause                                                          |
|ls /usr/share/nmap/scripts/* | grep ftp                                        |Search nmap scripts for keywords                                                                                                      |
