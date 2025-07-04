<!--
    Author: Kike Fontán (@CosasDePuma)
    Repository: Hackpack
    Description: An up-to-date collection of nuclei-templates, precompiled binaries and hacking scripts, taking advantage of the power of GitHub Actions.
-->

<div align="center">
    <hr/>
    <img src="logo.png" alt="Hackpack" />
    <br/> <br/>
    <img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/cosasdepuma/hackpack?style=for-the-badge"/>
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/cosasdepuma/hackpack?style=for-the-badge"/>
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/cosasdepuma/hackpack?style=for-the-badge"/>
    <img alt="GitHub Actions Workflow Status" src="https://img.shields.io/github/actions/workflow/status/cosasdepuma/hackpack/release.yml?style=for-the-badge"/>
    <hr />

## 📎 Windows Hackpack

| Tool                                                               | Description                                                                                                     |
| ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- |
| [Certify](https://github.com/GhostPack/Certify)                    | Active Directory certificate abuse.                                                                             |
| [Get-ServiceACL](./windows/Get-ServiceACL/Get-ServiceACL.ps1)      | Retrieve the access control list (ACL) for a service running on a host.                                         |
| [MailSniper](https://github.com/dafthack/MailSniper)               | Toolset for performing analysis and attacks on mail services.                                                   |
| [Powecat](https://github.com/besimorhino/powercat)                 | [Netcat](https://en.wikipedia.org/wiki/Netcat)-like written in PowerShell.                                      |
| [PowerLurk](https://github.com/Sw4mpf0x/PowerLurk)                 | Toolset for building malicious WMI event subscriptions.                                                         |
| [PowerSharpPack](https://github.com/S3cur3Th1sSh1t/PowerSharpPack) | Useful offensive C# projects wraped into Powershell for easy usage.                                             |
| [PowerSploit](https://github.com/PowerShellMafia/PowerSploit)      | PowerShell post-exploitation framework.                                                                         |
| [Rubeus](https://github.com/GhostPack/Rubeus)                      | Toolset for raw Kerberos interaction and abuses.                                                                |
| [Seatbelt](https://github.com/GhostPack/Seatbelt)                  | Security oriented host-survey "safety checks".                                                                  |
| [SharPersist](https://github.com/mandiant/SharPersist)             | Toolkit for Windows persistence.                                                                                |
| [SharpUp](https://github.com/GhostPack/SharpUp)                    | [PowerUp](https://github.com/PowerShellMafia/PowerSploit/blob/dev/Privesc/PowerUp.ps1)-like tool written in C#. |

<br/>

## ⚛️ Nuclei Templates

| Type | Proto | ID  | Description |
| ---- | ----- | --- | ----------- |
| 🔀 | SSH | [ssh-workflow](../nuclei-templates/workflows/ssh.yaml) | SSH workflow. |
| 📄 | SSH | [ssh-detect](../nuclei-templates/templates/ssh/detect.yaml) | Software detection via Banner Grabbing. |
| 📄 | SSH | [ssh-auth-password](../nuclei-templates/templates/ssh/auth-password.yaml) | Password-based authentication enabled. |
| 📄 | SSH | [ssh-weak-kex](../nuclei-templates/templates/ssh/weak-kex.yaml) | Weak key exchange algorithms offered. |
| 📄 | SSH | [ssh-weak-mac](../nuclei-templates/templates/ssh/weak-mac.yaml) | Weak message authentication code algorithms offered. |
| 📄 | SSH | [cve-2023-48795](../nuclei-templates/templates/ssh/cve-2023-48795.yaml) | Terrapin Attack. |

<hr/>
</div>
