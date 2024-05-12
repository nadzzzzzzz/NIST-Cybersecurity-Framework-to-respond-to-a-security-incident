# Security Response and Improvement Plan

## Introduction
This document outlines the cybersecurity strategy and response to a Distributed Denial of Service (DDoS) attack that targeted our company’s internal network. The attack temporarily disabled network services by overwhelming the network with ICMP packets. This README serves as a guide to applying the NIST Cybersecurity Framework (CSF) to improve our cybersecurity defenses.

## Table of Contents
1. Incident Overview
2. NIST Cybersecurity Framework Application
   - Identify
   - Protect
   - Detect
   - Respond
   - Recover
3. Improvement Plan
4. Conclusion

## 1. Incident Overview
**Event Description:** Our organization’s network services were halted for approximately two hours due to a DDoS attack involving an influx of ICMP packets.

**Immediate Actions Taken:**
- Blocking incoming ICMP packets.
- Taking non-critical network services offline.
- Restoring critical network services.

**Findings:**
- The attack was facilitated through an unconfigured firewall that failed to filter or rate-limit ICMP traffic.
- Malicious ICMP pings overwhelmed network resources, effectively disrupting operations.

## 2. NIST Cybersecurity Framework Application

### Identify
- **Asset Management:** Regular audits will be scheduled for all network devices and firewalls to identify unsecured configurations and outdated software.
- **Risk Assessment:** Perform comprehensive risk assessments focusing on vulnerabilities related to ICMP traffic and other potential DDoS vectors.

### Protect
- **Access Control:** Implement strict access controls to network configuration settings.
- **Awareness and Training:** Conduct training sessions on DDoS mitigation techniques and firewall management for IT staff.
- **Maintenance:** Establish routine checks and updates for all security devices to prevent exploitable vulnerabilities.

### Detect
- **Anomalies and Events:** Deploy network monitoring tools capable of detecting unusual increases in network traffic.
- **Security Continuous Monitoring:** Utilize the installed network monitoring software to observe traffic flows and identify deviations from normal patterns.

### Respond
- **Response Planning:** Develop and refine incident response plans specific to DDoS attacks.
- **Communications:** Establish clear communication channels for reporting and managing incidents among the cybersecurity team and other relevant departments.
- **Analysis:** Analyze the effectiveness of the response to the DDoS attack to identify areas for improvement.

### Recover
- **Recovery Planning:** Document and implement recovery protocols to quickly restore services after an attack.
- **Improvements:** Post-incident reviews to update recovery strategies and tools as necessary.

## 3. Improvement Plan
The following strategic improvements are proposed to enhance network resilience and response capabilities:
- **Firewall Configuration:** Implement advanced firewall rules including rate limiting for ICMP packets and verification of source IP addresses.
- **Deployment of IDS/IPS:** Integrate an Intrusion Detection System/Intrusion Prevention System (IDS/IPS) to filter potentially malicious ICMP traffic.
- **Enhanced Monitoring:** Increase the capability of existing network monitoring systems to detect and alert on abnormal ICMP traffic patterns.

## 4. Conclusion
This document outlines the application of the NIST CSF in response to a recent DDoS attack, providing a structured approach to strengthening our cybersecurity posture. By following this plan, we aim to protect against future attacks, detect threats more effectively, respond efficiently, and recover rapidly from incidents.

## Acknowledgements
Thank you to all team members and departments who participated in managing the incident and contributed to developing this improvement plan.
