# Security-Audit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Incident Summary</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        section {
            margin-bottom: 20px;
        }
        .section-title {
            font-weight: bold;
            text-transform: uppercase;
        }
    </style>
</head>
<body>

    <h1>Cybersecurity Incident Summary</h1>

    <section>
        <h2 class="section-title">Incident Overview</h2>
        <p><strong>Event:</strong> Distributed Denial of Service (DDoS) attack.</p>
        <p><strong>Impact:</strong> Disrupted internal network for two hours.</p>
        <p><strong>Cause:</strong> Massive influx of ICMP (Internet Control Message Protocol) packets.</p>
        <p><strong>Response:</strong> Blocked incoming ICMP packets, shut down non-critical network services, and restored essential services.</p>
    </section>

    <section>
        <h2 class="section-title">Investigation Findings</h2>
        <p><strong>Cause of Breach:</strong> Unconfigured firewall allowed attacker to execute DDoS attack.</p>
        <p><strong>Attack Method:</strong> Malicious actor exploited vulnerability, inundating network with ICMP pings.</p>
    </section>

    <section>
        <h2 class="section-title">Mitigation and Prevention Measures</h2>
        <h3>Protect</h3>
        <p><strong>New Firewall Rule:</strong> Implemented to limit the rate of incoming ICMP packets.</p>
        <p><strong>IDS/IPS System:</strong> Installed to filter out suspicious ICMP traffic.</p>

        <h3>Detect</h3>
        <p><strong>Source IP Address Verification:</strong> Configured on the firewall to verify authenticity and prevent spoofed IP addresses.</p>

        <h3>Respond</h3>
        <p><strong>Immediate Action:</strong> Identify and isolate affected systems to prevent further damage.</p>
        <p><strong>Analysis:</strong> Network logs will be analyzed for suspicious activity.</p>
        <p><strong>Reporting:</strong> Incidents will be reported to upper management and legal authorities if applicable.</p>

        <h3>Recover</h3>
        <p><strong>Restoration:</strong> Restore access to network services, starting with critical services.</p>
        <p><strong>Blocking:</strong> External ICMP flood attacks to be blocked at the firewall.</p>
        <p><strong>Service Management:</strong> Non-critical services to be stopped initially and brought back online after the attack subsides.</p>
    </section>

    <section>
        <h2 class="section-title">Reflections/Notes</h2>
        <p>The importance of regularly updating and configuring firewall settings.</p>
        <p>Continuous monitoring and improvement of network defenses.</p>
        <p>The need for a robust incident response plan to quickly mitigate and recover from cyber attacks.</p>
        <p>Ongoing training for the cybersecurity team to handle evolving threats effectively.</p>
    </section>

</body>
</html>
