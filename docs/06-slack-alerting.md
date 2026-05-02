# 06 - Slack Alerting

## Objective

Integrate Wazuh with Slack so alerts are pushed into a security operations channel in real time.

## Operational Workflow

1. Wazuh detects a security event.
2. The event is correlated against rules and alert thresholds.
3. A notification is sent into Slack.
4. Security team members review and triage the alert.
5. Optional ticketing workflows can be triggered through Slack integrations.

## Security Value

Slack alerting reduces the time between detection and human response. It also improves collaboration, visibility, and accountability for small teams that may not have a full 24/7 SOC.

## Public Repository Safety Note

Do not publish Slack webhook URLs, bot tokens, workspace invitation links, or app credentials.
