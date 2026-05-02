# 03 - File Integrity Monitoring

## Objective

Use Wazuh File Integrity Monitoring to detect unauthorised or unexpected changes to critical files and directories.

## Windows FIM

The Windows endpoint was configured to monitor selected directories and files. Wazuh generated alerts when test files were modified, proving that endpoint file activity could be tracked centrally.

## Linux FIM

Linux monitoring included sensitive system files such as `/etc/passwd`. Adding a user changed the file, and Wazuh generated an alert showing the file integrity event.

## Security Value

FIM helps detect:

- Unauthorised file changes
- Malware-related modifications
- Privilege persistence attempts
- Configuration drift
- Suspicious changes to sensitive system files

## Recruiter Relevance

This demonstrates practical knowledge of endpoint monitoring, change detection, integrity validation, and compliance-focused security controls.
