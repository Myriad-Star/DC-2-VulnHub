# DC-2 — VulnHub Penetration Testing Walkthrough

A practical penetration testing walkthrough of **DC-2**, an intentionally vulnerable virtual machine from VulnHub.

This repository documents the assessment process, from network reconnaissance and service enumeration to initial access and privilege escalation.

## Objectives

- Discover the target and identify exposed services.
- Enumerate the WordPress application and SSH service.
- Investigate potential entry points.
- Obtain initial access to the target.
- Identify and exploit a privilege escalation misconfiguration.
- Document findings and security weaknesses.

## Lab Environment

| Component | Details |
|---|---|
| Target | DC-2 (VulnHub) |
| Attacking Machine | Kali Linux |
| Virtualization | Oracle VirtualBox |
| Target IP | `192.168.1.10` |
| Open Ports | `80/tcp`, `7744/tcp` |

## Tools Used

Netdiscover, Nmap, CeWL, WPScan, SSH, Vim, Git.

## Methodology

1. **Reconnaissance:** Discover the target and identify exposed services.
2. **Enumeration:** Investigate WordPress users and authentication.
3. **Initial Access:** Gain access through the exposed SSH service.
4. **Privilege Escalation:** Investigate sudo permissions and obtain root access.
5. **Post-Exploitation:** Verify elevated privileges and retrieve the final flag.

## Repository Structure

```text
DC-2-VulnHub/
├── reconnaissance/
├── enumeration/
├── initial-access/
├── privilege-escalation/
├── screenshots/
└── README.md
```

## Disclaimer

This assessment was conducted in an isolated virtual lab for educational purposes. All activities were performed against the intentionally vulnerable DC-2 machine.