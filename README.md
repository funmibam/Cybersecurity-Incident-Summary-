# Cybersecurity Incident Summary

## Incident Overview
**Event:** Distributed Denial of Service (DDoS) attack.

**Impact:** Disrupted internal network for two hours.

**Cause:** Massive influx of ICMP (Internet Control Message Protocol) packets.

**Response:** Blocked incoming ICMP packets, shut down non-critical network services, and restored essential services.

## Investigation Findings
**Cause of Breach:** Unconfigured firewall allowed attacker to execute DDoS attack.

**Attack Method:** Malicious actor exploited vulnerability, inundating network with ICMP pings.

## Mitigation and Prevention Measures

### Protect
**New Firewall Rule:** Implemented to limit the rate of incoming ICMP packets.

**IDS/IPS System:** Installed to filter out suspicious ICMP traffic.

### Detect
**Source IP Address Verification:** Configured on the firewall to verify authenticity and prevent spoofed IP addresses.

### Respond
**Immediate Action:** Identify and isolate affected systems to prevent further damage.

**Analysis:** Network logs will be analyzed for suspicious activity.

**Reporting:** Incidents will be reported to upper management and legal authorities if applicable.

### Recover
**Restoration:** Restore access to network services, starting with critical services.

**Blocking:** External ICMP flood attacks to be blocked at the firewall.

**Service Management:** Non-critical services to be stopped initially and brought back online after the attack subsides.

## Reflections/Notes
- The importance of regularly updating and configuring firewall settings.
- Continuous monitoring and improvement of network defenses.
- The need for a robust incident response plan to quickly mitigate and recover from cyber attacks.
- Ongoing training for the cybersecurity team to handle evolving threats effectively.
