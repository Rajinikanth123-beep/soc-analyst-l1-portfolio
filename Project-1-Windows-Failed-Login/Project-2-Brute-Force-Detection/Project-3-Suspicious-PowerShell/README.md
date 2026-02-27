# ⚡ Project 3 – Suspicious PowerShell Execution

## Objective
Detect malicious PowerShell activity.

## Detection Logic
Alert when:
process.name: powershell.exe
AND command_line contains "-EncodedCommand"

## MITRE Mapping
T1059.001 – PowerShell

## Skills Demonstrated
- Process Monitoring
- Detection Engineering
- High Severity Alert Configuration
