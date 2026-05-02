# 08 - Operational Use Cases

## Use Case 1: Failed Login Detection

A failed login was simulated and Wazuh generated an alert. This validates authentication monitoring and brute-force detection foundations.

## Use Case 2: Windows File Change Detection

A monitored Windows test file was changed. Wazuh FIM detected the modification and displayed the event in the dashboard.

## Use Case 3: Linux Sensitive File Change

A Linux user account was added, which changed `/etc/passwd`. Wazuh detected the sensitive file update.

## Use Case 4: Malware Simulation with EICAR

The EICAR test file was used to validate Defender detection and Wazuh visibility.

## Use Case 5: Slack Alert Delivery

Wazuh alerts were pushed into Slack to demonstrate real-time collaboration and response notification.

## Use Case 6: Vulnerability Visibility

Wazuh vulnerability detection displayed endpoint risk information on the dashboard.
