# Ahmed Al Abdullah

### Cybersecurity · Detection Engineering · Threat Hunting

I focus on turning security events into clear investigation leads and reliable
detection logic. My work connects code with event timelines, reproducible evidence,
and tests that check both suspicious and expected behavior.

[LinkedIn](https://www.linkedin.com/in/ahmed-al-abdullah) ·
[Repositories](https://github.com/AhmedAlAbdullah0?tab=repositories) ·
[Detection Replay](https://github.com/AhmedAlAbdullah0/detection-replay) ·
[Authentication Threat Hunting](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting)

**2 projects · 32 behavioral tests · Automated checks on Windows and Linux**

## Selected work

| Project | Engineering question | Verified result |
|---|---|---|
| [Detection Replay](https://github.com/AhmedAlAbdullah0/detection-replay) | How can a scheduled detection recover late events without repeatedly alerting on them? | 6 alerts reduced to 2, with 0 duplicates; 12 tests |
| [Authentication Threat Hunting](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting) | How can failure bursts, multi-account attempts, and subsequent successes be correlated? | 3 findings from 39 included events; 20 tests |

### Detection Replay

[![Validation](https://github.com/AhmedAlAbdullah0/detection-replay/actions/workflows/validation.yml/badge.svg)](https://github.com/AhmedAlAbdullah0/detection-replay/actions/workflows/validation.yml)

Python and SQLite analysis of Windows Security event 4732. The replay separates
event time from index time, recovers a delayed record with a wider lookback,
and uses a compound alert identity to suppress repeated delivery within the replay.

![Detection replay results](https://raw.githubusercontent.com/AhmedAlAbdullah0/detection-replay/main/Detection_Replay.jpg)

[Source and evidence](https://github.com/AhmedAlAbdullah0/detection-replay) ·
[Query view](https://github.com/AhmedAlAbdullah0/detection-replay/blob/main/Detection_Query.png) ·
[Automated validation](https://github.com/AhmedAlAbdullah0/detection-replay/actions/workflows/validation.yml)

### Authentication Threat Hunting

[![Validation](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting/actions/workflows/validation.yml/badge.svg)](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting/actions/workflows/validation.yml)

A Python engine for rolling-window logon correlation, supported by an investigation
timeline, explicit negative controls, and Splunk candidate searches. Tests check
window boundaries, source/account isolation, event ordering, and allowlisting.

![Authentication event evidence](https://raw.githubusercontent.com/AhmedAlAbdullah0/authentication-threat-hunting/main/evidence-overview.png)

[Detection engine](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting/blob/main/hunt.py) ·
[Investigation](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting/blob/main/INVESTIGATION.md) ·
[Validation record](https://github.com/AhmedAlAbdullah0/authentication-threat-hunting/blob/main/VALIDATION.md)

## Technical focus

- Windows authentication and account-management event analysis
- Detection testing, event correlation, and alert deduplication
- Threat-hunting hypotheses and evidence-based investigation reporting

**Technologies in these repositories:** Python · SQLite · Windows Security Events · Splunk SPL

## Credentials

- CompTIA Security+ (SY0-701), 2026
- Certified Associate in Project Management (CAPM), PMI, 2025
- BSc in Computer Science, King Khalid University, 2025

## Approach

Runnable code, traceable evidence, and clear validation records. Each repository
documents its data, checked behavior, and engineering boundaries. Investigation
findings are assessed against their context and alternative explanations.
