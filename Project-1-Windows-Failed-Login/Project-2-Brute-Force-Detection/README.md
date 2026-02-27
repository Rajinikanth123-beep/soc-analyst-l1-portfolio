![project2](https://github.com/user-attachments/assets/42f92c37-c3bf-4091-80a2-12525ae5f1de)
# 🚨 Project 2 – Brute Force Detection

## Objective
Detect multiple failed login attempts indicating brute-force attack.

## Event ID
4625 – Failed Login

## Detection Logic
Threshold rule:
5+ failed attempts
Same source IP
Within 5 minutes

## MITRE Mapping
T1110 – Brute Force

## Skills Demonstrated
- Threshold Rule Creation
- Alert Configuration
- Attack Pattern Detection
