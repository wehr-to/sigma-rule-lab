# Sigma Rule Lab 🧪

Welcome to the Sigma Rule Lab, a structured repo for learning how to write, test, and simulate Sigma rules like a modern blue teamer or security engineer.

## 🔎 What is Sigma?

Sigma is a generic rule format for SIEM detection — the **YAML of blue team detection engineering**. Think of it like:
- **Snort rules for logs**
- **YARA for detection logic**
- **SIEM-agnostic detection-as-code**

## 💡 What This Repo Covers

### Intro to Sigma
- What Sigma is
- How Sigma compares to YARA, Snort, etc.
- Rule syntax and structure

### Core Fields and Logic
- `logsource`, `detection`, `condition`
- Field modifiers (`contains|all|endswith`)
- FP handling and severity levels

### Rule Examples (Security Use Cases)
- Powershell abuse
- DLL injection
- Credential dumping (Mimikatz)
- DNS tunneling
- Suspicious binaries in unusual paths

### Testing Rules
- Using `sigmac` CLI
- Testing against sample logs
- Converting to Splunk, Elastic, Sentinel, etc.
- Alert simulation tips

### Red-Blue Playground
- Simulated attacker payloads
- Matching Sigma rules to catch them

## 🧰 Tools You'll Use
- [sigma-cli](https://github.com/SigmaHQ/sigma-cli)
- [Sigmac](https://github.com/SigmaHQ/sigmac)
- Fake log generators (optional)
- Log conversion tools (for Splunk/Elastic)

## 📎 Ideal For:
- Aspiring SOC analysts
- Detection engineers
- Threat hunters
- Students learning detection-as-code
