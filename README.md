# SharpNado

Repository to link to the tools or implementations related with malware I will be writting in C#:

- [GetModuleHandle](https://github.com/ricardojoserf/GetModuleHandle): GetModuleHandle implementation in C# using only NtQueryInformationProcess by walking the PEB in 32-bit or 64-bit processes

- [GetProcAddress](https://github.com/ricardojoserf/GetProcAddress): GetProcAddress implementation in C# using only NtReadVirtualMemory by walking the PEB in 32-bit or 64-bit processes

- [GetProcessByName](https://github.com/ricardojoserf/GetProcessByName): Get processes from process name using NtGetNextProcess and GetProcessImageFileName syscalls

- [GuardPagesHooking](https://github.com/ricardojoserf/GuardPagesHooking): C# implementation of Guard Pages API Hooking (also known as VEH hooking)

- [jeringuilla](https://github.com/ricardojoserf/jeringuilla): Process injection framework in C#. It uses dynamic function loading using delegates and AES-encryption for strings and payloads

- [lsass-dump-csharp](https://github.com/ricardojoserf/lsass-dumper-csharp): Dump lsass.exe generating a file with the hostname and date in txt format using C#

- [Non-ms-binaries](https://github.com/ricardojoserf/non-ms-binaries): Code snippet to create a process using the "PROCESS_CREATION_MITIGATION_POLICY_BLOCK_NON_MICROSOFT_BINARIES_ALWAYS_ON" flag

- [SharpADS](https://github.com/ricardojoserf/SharpADS): Read, write and delete Alternate Data Streams (ADS) within NTFS, to hide malicious payloads

- [SharpCovertTube](https://github.com/ricardojoserf/SharpCovertTube): Youtube as covert-channel - Control Windows systems remotely and execute commands by uploading videos to Youtube

- [SharpEA](https://github.com/ricardojoserf/SharpEA): Read, write and delete Extended Attributes (EAs) within NTFS, to hide malicious payloads

- [SharpNtdllOverwrite](https://github.com/ricardojoserf/SharpNtdllOverwrite): Overwrite ntdll.dll ".text" section to bypass API hooking. Getting the clean ntdll.dll from disk, Knowndlls folder, a debugged process or a URL

- [SharpSelfDelete](https://github.com/ricardojoserf/Sharpselfdelete): PoC to self-delete a binary in C#. The process continues but the .exe file is removed from disk

- [StealthyEnv](https://github.com/ricardojoserf/StealthyEnv): Stealthier alternative to whoami.exe in C#, it gets environment variables from PEB (PRTL_USER_PROCESS_PARAMETERS)

- [WhoamiAlternatives](https://github.com/ricardojoserf/WhoamiAlternatives): Different methods to get current username without using whoami, based on vx-underground posts


<p align="center">
  <img width="420" src="https://raw.githubusercontent.com/ricardojoserf/ricardojoserf.github.io/master/images/sharpnado/test2.drawio.png">
</p>
