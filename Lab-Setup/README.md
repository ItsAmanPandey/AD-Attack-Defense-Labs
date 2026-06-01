# Lab Setup

## Overview

The lab is an isolated Active Directory environment hosted in VirtualBox. It contains one domain controller, two domain-joined Windows workstations, and one Kali Linux attacker machine.

## Virtual Machines

| Role | VM Name | Operating System | CPU | Memory | Network |
|---|---|---|---|---:|---|
| Domain Controller | Windows Server(AD) | Windows Server 2022 64-bit | 2 vCPU | 2048 MB | NatNetwork |
| Workstation | SPIDERMAN | Windows 11 64-bit | 2 vCPU | 4096 MB | NatNetwork |
| Workstation | THEPUNISHER | Windows 11 64-bit | 2 vCPU | 4096 MB | NatNetwork |
| Attacker | kali-linux-2026.1-virtualbox-amd64 | Debian 64-bit, Kali Linux 2026.1 | 2 vCPU | 4096 MB | NatNetwork |

## Lab Theme

The lab uses a Marvel naming theme:

- `SPIDERMAN` as a Windows workstation
- `THEPUNISHER` as a Windows workstation
- `Windows Server(AD)` as the domain controller
- `kali-linux-2026.1-virtualbox-amd64` as the attacker machine

## Network Notes

All systems are connected to the same VirtualBox `NatNetwork`, allowing the attacker machine and Windows domain systems to communicate inside the lab. The environment should remain isolated from production or personal networks when performing offensive security testing.

## Safety Notes

- Do not reuse real credentials in the lab.
- Do not publish cracked passwords or raw credential material.
- Keep all attacks contained to lab-owned systems.
- Take snapshots before major configuration changes.
