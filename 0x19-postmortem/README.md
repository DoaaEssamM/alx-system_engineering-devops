Issue Summary:

Duration: The outage occurred from 10:00 AM to 12:30 PM on February 15, 2024 (UTC+0).
Impact: The outage affected the company's main website, resulting in a complete unavailability of the service. Approximately 80% of the users trying to access the website during this time experienced slow loading times or were unable to connect altogether.
Root Cause: The root cause of the outage was identified as a misconfiguration in the load balancer settings, leading to an overload on one of the web servers.
Timeline:

10:00 AM: The issue was detected when the monitoring system triggered an alert for unusually high server response times.
10:15 AM: Engineers began investigating the issue, suspecting potential network or server issues.
10:45 AM: After ruling out network issues, attention turned to server performance and load balancing configurations.
11:30 AM: A configuration error in the load balancer settings was identified as the likely cause of the issue.
12:00 PM: The incident was escalated to the DevOps team for immediate resolution.
12:30 PM: The misconfiguration in the load balancer settings was corrected, and the website service was restored to normal functionality.
Root Cause and Resolution:

Root Cause: The issue stemmed from a misconfigured load balancer, which was inadvertently directing all incoming traffic to a single web server, causing it to become overloaded and unresponsive.
Resolution: Engineers reconfigured the load balancer settings to evenly distribute incoming traffic across all available web servers. Additionally, they implemented stricter monitoring and alerting systems to quickly identify and address any similar issues in the future.
Corrective and Preventative Measures:

Improvements/Fixes:

Regular audits of load balancer configurations to ensure proper distribution of traffic.
Enhanced monitoring of server performance metrics to detect anomalies early.
Documentation updates to document best practices for load balancer configuration and maintenance.
Tasks to Address the Issue:

Conduct a thorough review of load balancer configurations and implement automated checks to prevent similar misconfigurations.
Enhance internal communication and escalation procedures to streamline incident response processes.
Schedule regular training sessions for engineering teams to increase awareness of common infrastructure issues and troubleshooting techniques.
By implementing these corrective measures and proactive steps, the company aims to minimize the risk of similar outages in the future and ensure a reliable and resilient service for its users.
