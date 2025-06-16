# reverse-sha-pass
Reverse engineer SHA1_Pass-v1.4

**WARNING**: This software is copyrighted, so I did not continue.

## Prerequisites
Follow these instructions for the latest installation notes:

https://github.com/NationalSecurityAgency/ghidra/blob/Ghidra_11.3.2_build/GhidraDocs/InstallationGuide.md#software

### Steps I Used

- `winget install Amazon.Corretto.21.JDK`
  - Ensured `JAVA_HOME` was an environment variable by opening a new shell and running: `echo $env:JAVA_HOME`
- Download the latest [Ghidra release](https://github.com/NationalSecurityAgency/ghidra/releases)
- Unzipped into a directory and ran the `ghidraRun.bat`
  - Do not run into this error: `ERROR: Ghidra path cannot contain a "!" character.`
- Create a new project: Non-Shared
  - Drag `.exe` into Ghidra project 
