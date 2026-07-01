# Post-Compromise Attacks

This section documents attacks performed after valid credentials or hashes have already been obtained in the Active Directory lab.

## Reports

| Attack | Status | Summary |
|---|---|---|
| [Pass Attacks](./Pass-Attacks.md) | Complete | Tested pass-the-password and pass-the-hash techniques with CrackMapExec and Impacket. |
| [Token Impersonation](./Token-Impersonation.md) | Complete | Used Metasploit Meterpreter and Incognito to impersonate domain tokens and perform privileged domain actions. |
| [LNK File Attack](./LNK-File-Attack.md) | Complete | Created a malicious shortcut on a file share and captured an NTLMv2 hash with Responder. |

## Scope

These reports focus on how post-compromise access can be used for lateral movement, credential dumping, share enumeration, and privilege expansion in the lab.
