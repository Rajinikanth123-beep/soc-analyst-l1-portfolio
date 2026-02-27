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
