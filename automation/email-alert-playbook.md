# Email Alert Playbook – SSH Brute Force Detection

## Overview
This playbook automates analyst notification when an SSH brute-force incident is created in Microsoft Sentinel.

It is designed to provide immediate visibility of suspicious activity without requiring manual monitoring of the SIEM.

---

## Trigger
- Microsoft Sentinel
- Event: **When an incident is created**

---

## Conditions
- Incident title contains: `Linux SSH Brute Force Detected`

---

## Actions
- Send email notification via Azure Logic Apps

---

## Outcome
- Analysts are notified in near real time
- Reduces mean time to detection (MTTD)
- Demonstrates SOAR capability in a SOC workflow
