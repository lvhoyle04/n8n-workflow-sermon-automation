# Rate Limit & Abuse Detection Workflow

## Purpose
Monitors webhook or API usage and logs access rates by IP or user. Alerts if thresholds are exceeded.

## Use Case
- Detect brute-force login attempts
- Spot misconfigured bots

## Features
- Tracks per-IP request frequency
- Sends alerts for rate spikes
- Optional: blocks IP or logs it

## Requirements
- Google Sheet or Airtable for logging
