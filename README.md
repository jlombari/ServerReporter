# Server Reporter
## _A C# SysAdmin tool_
![Build Status](https://badgen.net/badge/Release/unreleased/red?icon=github)
![Source Status](https://badgen.net/badge/Source/temp-closed/red?icon=terminal)
![Framework](https://badgen.net/badge/.NET/7.0.9/green?icon=windows)
 ![License](https://badgen.net/badge/License/null)

Server Reporter automates common SysAdmin tasks and
generates an HTML report with the task results.
- Target: Windows Servers 2019+
- Works on Windows 10+ Desktop too!
- Depends on .NET 7
- Coming Soon: Linux support

## Automated Tasks

- Retreive Hardware details
- chkdsk on C:
- SFC /ScanNow
- Disk Cleanup sagerun:1
- AD Health report (Checks if local device is in a domain, then performs health check on entire forest)
- Internet Speed Test by ookla

## TODO

- Add alternative sagerun modes to choose from before running
- Add pre-run environment check to determine runtime variables per OS
