
# Incident Handler’s Journal

This document contains a series of incident investigation entries recorded in an
Incident Handler’s Journal. Each entry documents the detection, analysis, tools
used, and lessons learned during the investigation of a security-related event.

The purpose of this journal is to demonstrate how a SOC analyst observes,
documents, and reasons through security incidents in a structured and
professional manner.

---

## Incident Entry 1: Suspicious Network Traffic Detected

### Date
2023-XX-XX

### Description of the Event
Unusual network traffic was detected while monitoring packet captures. The
traffic appeared abnormal when compared to baseline behavior and warranted
further investigation to determine whether it was malicious or benign.

### Detection Method
- Network traffic analysis during packet capture review

### Tools Used
- Wireshark
- tcpdump

### Investigation and Observations
Packet inspection revealed unexpected communication patterns and abnormal
packet structures. The source and destination addresses, along with protocol
usage, were reviewed to identify indicators of compromise or misconfiguration.

### Actions Taken
- Captured and reviewed relevant packets
- Isolated suspicious traffic for deeper analysis
- Documented findings for further review

### Lessons Learned
Continuous monitoring of network traffic is critical for early detection of
potential security incidents. Understanding normal traffic patterns helps
quickly identify anomalies.

---

## Incident Entry 2: Analysis of Potentially Malicious File

### Date
2023-XX-XX

### Description of the Event
A file was identified as potentially suspicious during routine analysis. The
file required further investigation to determine whether it posed a security
risk to the system.

### Detection Method
- Manual inspection of file behavior and indicators

### Tools Used
- VirusTotal

### Investigation and Observations
The file hash was submitted to VirusTotal for analysis. Results showed mixed
detections across different security engines, indicating potential malicious
characteristics but requiring cautious interpretation.

### Actions Taken
- Analyzed VirusTotal results
- Compared detection results across engines
- Assessed the potential impact if executed in the environment

### Lessons Learned
Threat intelligence platforms provide valuable context, but results must be
analyzed critically. A single detection does not always confirm malicious
intent.

---

## Incident Entry 3: Suspicious External Connection Attempt

### Date
2023-XX-XX

### Description of the Event
An external connection attempt was observed targeting internal network
resources. The activity appeared unusual and required investigation to assess
risk.

### Detection Method
- Review of captured network traffic

### Tools Used
- tcpdump
- Wireshark

### Investigation and Observations
The connection attempt originated from an unfamiliar external IP address. The
traffic pattern suggested scanning or probing behavior rather than normal user
activity.

### Actions Taken
- Logged the source IP address
- Reviewed traffic patterns for repetition
- Flagged the activity for further monitoring

### Lessons Learned
Early identification of probing activity allows security teams to respond
before escalation. Logging and correlation are essential in detecting repeated
patterns.

---

## Incident Entry 4: Reflection on Incident Response Process

### Summary
Across all investigated events, consistent documentation and structured
analysis improved clarity and response effectiveness.

### Key Takeaways
- Clear documentation supports better decision-making
- Tool output must be interpreted within context
- Incident handling is both technical and analytical
- Post-incident reflection improves future response

---

## Overall Observations

This journal highlights the importance of:
- Maintaining detailed incident records
- Applying multiple tools during investigations
- Thinking critically about alerts and indicators
- Continuously improving incident response skills

The documented entries reflect realistic scenarios faced by SOC analysts and
demonstrate practical incident-handling experience.

---

