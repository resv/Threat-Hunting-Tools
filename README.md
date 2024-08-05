# 🔎 Threat Hunter`s Collection (THC) [![resv - Threat-Hunters-Collection-THC](https://img.shields.io/static/v1?label=resv&message=Threat-Hunters-Collection-THC&color=blue&logo=github)](https://github.com/resv/Threat-Hunters-Collection-THC "Go to GitHub repo") [![stars - Threat-Hunters-Collection-THC](https://img.shields.io/github/stars/resv/Threat-Hunters-Collection-THC?style=social)](https://github.com/resv/Threat-Hunters-Collection-THC) [![forks - Threat-Hunters-Collection-THC](https://img.shields.io/github/forks/resv/Threat-Hunters-Collection-THC?style=social)](https://github.com/resv/Threat-Hunters-Collection-THC) [![GitHub release](https://img.shields.io/github/release/resv/Threat-Hunters-Collection-THC?include_prereleases=&sort=semver&color=blue)](https://github.com/resv/Threat-Hunters-Collection-THC/releases/) [![License](https://img.shields.io/badge/License-MIT-blue)](#license) [![issues - Threat-Hunters-Collection-THC](https://img.shields.io/github/issues/resv/Threat-Hunters-Collection-THC)](https://github.com/resv/Threat-Hunters-Collection-THC/issues)

The Threat Hunter's Collection is a single PowerShell script that consolidates a diverse array of tools from open-source projects, creating a comprehensive toolkit for cyber threat hunters.

This collection aims to simplify the threat hunting process by providing a single point of access to various tools, eliminating the need for tedious setup, sourcing downloads, or complex commands.

The toolkit promotes portability, allowing hunters to be creative—whether on a USB drive, as an email template, or CURL it from a repository for convenient and efficient threat hunting on the go. Explore the tools, contribute to the project, and enhance your threat hunting capabilities with the Threat Hunter's Collection.
## ✅ Features

- Host Info - Enumerate host info + stdoutu to an exportable .txt File
- [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) - Log system activity to the Windows Event Log
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) - Hunt via Sysmon & Windows Event Logs
- [AutoRuns](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns) - Hunt for scheduled tasks and persistence.
- [ProcMon](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) - Hunt file system, registry, & process/thread activity
- [ProcExp](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) - Hunt DLLs Processes
- [TCPView](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) - Hunt all TCP and UDP connections
- [AccessEnum](https://learn.microsoft.com/en-us/sysinternals/downloads/accessenum) - Hunt file system, registry, permissions security settings
- [WizTree](https://diskanalyzer.com/) - Hunt file structure



## ⚙️ How to Start

1. Download the single [THC](https://github.com/resv/Threat-Hunters-Collection-THC/raw/main/THC.ps1) powershell script (Optional: You can move the script to your desktop)

![Step 1 Download](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/Download.png?raw=true)

2. Run a powershell terminal as administrator.

![Step 2 OpenPS](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/OpenPS.png?raw=true)

3. Traverse to your download folder or desktop (depending on where THC.ps1 is)

![Step 3 Traverse to Directory](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/Traverse%20to%20file%20directory.png?raw=true)

4. Enable scripting by pasting this to your terminal (also found in the first line of the powershell script so you don't have to come here to copy pasta)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **```powershell.exe -noprofile -executionpolicy bypass -file .\THC.ps1```**

![Step 4a EnableScripting](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/RunOnce.png?raw=true)

5. [Optional] You can unrestrict for repetitive usage, then run THC.ps1

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **```Set-ExecutionPolicy RemoteSigned```**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **```.\THC.ps1```**

![Step 4b EnableScripting](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/RunMore.png?raw=true)

 - Don't forget to unrestrict when you leave

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **```Set-ExecutionPolicy Res```**

![Step 4c EnableScripting](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/RunMoreClose.png?raw=true)

6. Hunt 😎

![Step 4c EnableScripting](https://github.com/resv/Threat-Hunters-Collection-THC/blob/main/ReadmeIMGS/RunMoreClose.png?raw=true)


## ℹ️ Things to note

To be added later.

Sysmon: Pre-req

Please always exercise caution, use only if authorized.


## 😊 About Me
I'm a cybersecurity engineer for an primarily for the financial industry, along with many SMB clients.

[Linkedin](https://www.linkedin.com/in/adamkim456/) | [Discord](https://discord.gg/HXNprdRD) | [GitHub](https://github.com/resv) | Email: adam@atomkim.com    

[![Resv's github stats](https://github-readme-stats.vercel.app/api?username=resv)](https://github.com/resv) [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=resv&layout=compact)](https://github.com/resv)
## Feedback

If you have any feedback for suggestions, bugs, or ideas please reach out at adam@atomkim.com

