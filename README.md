# Active Directory Attack and Defense Labs

This repository documents a hands-on Active Directory homelab built to practice common enterprise attack paths and their defensive controls in an isolated environment.

The lab uses a Marvel-themed domain environment with a Windows Server domain controller, two Windows workstations, and a Kali Linux attacker machine.

## Lab Environment

| Role | System | VM Name | Notes |
|---|---|---|---|
| Domain Controller | Windows Server 2022 | Windows Server(AD) | Active Directory Domain Services |
| Workstation | Windows 11 | SPIDERMAN | Domain joined client |
| Workstation | Windows 11 | THEPUNISHER | Domain joined client |
| Attacker | Kali Linux 2026.1 | kali-linux-2026.1-virtualbox-amd64 | Offensive tooling |

## Sections

| # | Topic | Status |
|---|---|---|
| 1 | [Initial Attacks](./01-Initial-Attacks/) | In Progress |
| 2 | Post-Compromise Enumeration | Upcoming |
| 3 | Post-Compromise Attacks | Upcoming |
| 4 | Domain Compromise | Upcoming |
| 5 | Additional Attacks | Upcoming |

## Reports

- [LLMNR Poisoning](./01-Initial-Attacks/LLMNR-Poisoning.md)
- [SMB Relay Attack](./01-Initial-Attacks/SMB-Relay-Attack.md)
- [Gaining Shell Access](./01-Initial-Attacks/Gaining-Shell-Access.md)

## Tools Used

- Responder
- Hashcat
- Nmap
- NetExec
- Impacket
- VirtualBox
- Kali Linux
- Windows Server
- Windows 11

## Disclaimer

This repository is for educational purposes only. All activity documented here was performed inside an isolated lab environment owned and controlled by the author. Do not use these techniques on systems or networks without explicit authorization.
