# DFIR Incident Investigation & DNS Exfiltration Analysis

## Overview

Conducted a DFIR investigation to reconstruct an attack timeline and identify a simulated DNS data exfiltration attempt.

## Investigation

- Analyzed the exploitation phase and identified the attack endpoint.
- Investigated Sysmon logs to identify suspicious executions and service account activity.
- Correlated DNS activity with disk image artifacts to investigate the exfiltration channel.
- Identified DNS tunneling as the method used for data exfiltration.
- Used NetFlow data to validate suspicious DNS behavior through query frequency, packet sizes, and repetitive communication patterns.
- Correlated evidence from multiple data sources to build a complete attack timeline.

## Key Techniques

- Digital Forensics
- Network Forensics
- Incident Response
- Threat Hunting
- DNS Tunneling Analysis
- NetFlow Analysis
- Sysmon Log Analysis

## Key Takeaways

- Correlating multiple sources of evidence helps reconstruct an attack timeline.
- DNS traffic can be used as a data exfiltration channel.
- NetFlow data can help validate suspicious DNS communication patterns.
- Sysmon logs can provide valuable evidence during incident investigations.
