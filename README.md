<div align="center">

# Sunil Chikkala

### Security Analyst | Threat Hunter | SOC

*Finding the signal in the noise.*

![Experience](https://img.shields.io/badge/Experience-4_Years-0A1F44?style=for-the-badge)
![eCTHP](https://img.shields.io/badge/Certified-eCTHP-1A56B0?style=for-the-badge)
![Threat Hunting](https://img.shields.io/badge/Threat_Hunting-0A1F44?style=for-the-badge)
![SOC](https://img.shields.io/badge/SOC_Operations-1A56B0?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-0A1F44?style=for-the-badge)

</div>

---

## About me

I'm a Security Analyst with 4 years of experience, focused on threat hunting and SOC
operations. Security is my passion. My day-to-day work is reading logs, learning what normal
looks like, and spotting the anomalies that don't fit. When something looks wrong, I follow
it back to its source, work out what happened, and turn that knowledge into stronger defences.

## What I do

- **Log analysis:** reading endpoint and security logs to build a clear timeline of activity
- **Anomaly spotting:** noticing behaviour that stands out from what's normal for a system or user
- **Threat hunting:** looking for attacker behaviour that alerts didn't catch
- **SOC operations:** investigating alerts and separating real threats from noise
- **Detection engineering:** building and tuning detections mapped to MITRE ATT&CK
- **Automation:** using Python to reduce repetitive security work

## Anomalies I look for

- Encoded or hidden PowerShell commands
- Processes with an unusual parent, such as an Office app starting a shell
- System tools running from the wrong folder, or pretending to be something else
- Unexpected access to LSASS, which can signal credential theft
- Bursts of discovery commands such as `whoami`, `hostname` and `net`
- Unusual logins, new accounts and new persistence
- Odd outbound connections from processes that shouldn't need them

## How I investigate

1. **Understand normal:** know what's expected for the host, user and time
2. **Find the outlier:** pick out the event that doesn't fit
3. **Build the timeline:** connect related logs, processes and users
4. **Rule out harmless causes:** check for admin tools and expected activity
5. **Decide and improve:** report what happened, then tune detections to catch it sooner

## Experience and certification

- **4 years** in security, focused on threat hunting and SOC work
- **eCTHP:** Certified Threat Hunting Professional

## My detections

- [View my published detection on detections.ai](https://detections.ai/rules/01a18dec-d59f-738a-a5fc-5a31fd0ee1f5)

## Why security

Security is my passion. Every investigation is a puzzle with a real adversary on the other
side, and the field never stands still, so there's always something new to learn.

## Let's connect

Happy to talk about threat hunting, SOC operations and detection engineering.
