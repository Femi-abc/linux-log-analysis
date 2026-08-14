Linux log analysis report

Objective

Analyze Linux system logs and basic system information in a Kali Linux virtual lab environment.

Environment

- Operating system: Kali Linux
- Platform: VirtualBox
- Analysis type: Local system log investigation

System information

Basic system information was reviewed using standard Linux commands. Sensitive information such as the actual username, hostname, and personal file paths was intentionally redacted for privacy.

Recent log analysis

Recent system log entries were examined using:

journalctl -n 50

The review identified normal operating system activity, background services, and network-related events generated during the lab session.

Authentication log analysis

Authentication-related events were investigated using available log sources. No suspicious authentication activity was identified during the analysis period.

Commands used

- journalctl -n 50
- uname -a
- grep -i ssh /var/log/auth.log (or equivalent log source)

Findings

- System logs were successfully reviewed.
- Recent operating system events were identified.
- Authentication activity was examined.
- Basic log investigation techniques were demonstrated.

Skills demonstrated

- Linux log analysis
- System investigation
- Command-line analysis
- Log filtering
- Technical documentation

Conclusion

This exercise demonstrated the ability to inspect Linux system logs, review authentication-related events, and document findings in a structured technical report while protecting sensitive system information.
