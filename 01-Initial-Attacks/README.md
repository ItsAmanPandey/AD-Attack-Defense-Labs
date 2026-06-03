# Initial Attacks

This section documents initial access and early-stage attack techniques against the Active Directory lab environment.

## Reports

| Attack | Status | Summary |
|---|---|---|
| [LLMNR Poisoning](./LLMNR-Poisoning.md) | Complete | Captured and cracked an NTLMv2 hash using Responder and Hashcat in the lab environment. |
| [SMB Relay Attack](./SMB-Relay-Attack.md) | Complete | Relayed NTLM authentication with Responder and Impacket after identifying a target without required SMB signing. |
| [Gaining Shell Access](./Gaining-Shell-Access.md) | Complete | Tested Impacket psexec.py, wmiexec.py, and smbexec.py for remote shell access using passwords and hashes. |

## Scope

These reports focus on how the attack works, the lab commands used, evidence collected, and practical mitigation steps.
