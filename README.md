# VAPT – System Hacking Assessment

## Vulnerability Information

* **Severity:** Critical
* **Target Machine:** Microsoft Windows 7 Professional
* **Environment:** Controlled Lab Environment

## Enumeration

### Command

```bash
nmap -A 192.168.190.128
```

### Findings

```text
Host Status: Up
Operating System: Microsoft Windows 7 Professional
Architecture: 32-bit
Services: Identified during enumeration
```

## Exploitation

A security assessment was conducted to validate the impact of a remote access vulnerability within an authorized lab environment.

## Result

Remote shell access obtained.

## Privilege Escalation

### Objective

Determine whether elevated privileges could be obtained after initial access.

### Result

Privilege escalation was successfully achieved, resulting in elevated access on the target system.

## Screenshot

<img width="811" height="414" alt="admin access" src="https://github.com/user-attachments/assets/1278a395-c056-4485-a1a4-437ba4bfdf56" />

## Impact

* Remote command execution
* Unauthorized system access
* Access to sensitive information
* Ability to modify system configurations
* Potential for persistence and lateral movement
* Full system compromise after privilege escalation

## Remediation

* Keep operating systems updated.
* Apply security patches regularly.
* Restrict unnecessary services.
* Use endpoint protection solutions.
* Monitor suspicious activity and logs.
* Enforce the principle of least privilege.
* Remove unnecessary administrator privileges.
* Conduct regular vulnerability assessments.

## Skills Demonstrated

* Network Enumeration
* Vulnerability Assessment
* System Hacking
* Privilege Escalation Assessment
* Risk Analysis
* Security Documentation
* Remediation Planning

## Disclaimer

This project was performed in a controlled and authorized laboratory environment for educational and security research purposes only.

## Author

**Gulamnabi Khan**
