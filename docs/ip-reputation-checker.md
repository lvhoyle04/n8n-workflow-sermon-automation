# IP Reputation Checker Workflow

## Purpose
Scans a user-submitted or system-logged IP address using AbuseIPDB or VirusTotal and returns a trust score.

## Use Case
- Block spam IPs from comment forms
- Flag suspicious activity on sermon dashboards

## Requirements
- API key for [AbuseIPDB](https://www.abuseipdb.com/) or [VirusTotal](https://www.virustotal.com/)

## Inputs
- IP address (from webhook, form, or log)

## Outputs
- Score or risk assessment
- Optional Slack or email alert
