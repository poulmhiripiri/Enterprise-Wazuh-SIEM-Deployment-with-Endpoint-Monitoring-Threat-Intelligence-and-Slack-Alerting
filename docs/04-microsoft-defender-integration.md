# 04 - Microsoft Defender Integration

## Objective

Forward Microsoft Defender operational events into Wazuh to centralise endpoint malware visibility.

## Configuration Concept

The Wazuh Windows agent can collect Defender events from the Microsoft Defender Operational event channel.

Example configuration block:

```xml
<localfile>
  <location>Microsoft-Windows-Windows Defender/Operational</location>
  <log_format>eventchannel</log_format>
</localfile>
```

## Test Case

The lab used the EICAR test file to validate malware event visibility. Defender detection events were collected and presented through Wazuh for investigation.

## Security Value

This integration helps security teams correlate endpoint malware activity with other events such as file integrity changes, login failures, and vulnerability findings.
