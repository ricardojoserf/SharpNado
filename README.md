# SharpNado

Repository to link to the tools or implementations related with malware I will be writting in C#:

- [FakeRebootAlert](https://github.com/ricardojoserf/FakeRebootAlert): Simple Windows Forms App to deceive users into rebooting the system upon login 

- [GetModuleHandle](https://github.com/ricardojoserf/GetModuleHandle): GetModuleHandle implementation in C# using only NtQueryInformationProcess by walking the PEB in 32-bit or 64-bit processes

- [GetModuleHandleRemote](https://github.com/ricardojoserf/GetModuleHandleRemote): GetModuleHandle implementation in C# for remote processes using only NTAPIs

- [GetProcAddress](https://github.com/ricardojoserf/GetProcAddress): GetProcAddress implementation in C# using only NtReadVirtualMemory by walking the PEB in 32-bit or 64-bit processes

- [GetProcessByName](https://github.com/ricardojoserf/GetProcessByName): Get processes from process name using NtGetNextProcess and GetProcessImageFileName syscalls

- [GuardPagesHooking](https://github.com/ricardojoserf/GuardPagesHooking): C# implementation of Guard Pages API Hooking (also known as VEH hooking)

- [Jeringuilla](https://github.com/ricardojoserf/jeringuilla): Process injection framework in C#. It uses dynamic function loading using delegates and AES-encryption for strings and payloads

- [Lsass-dump-csharp](https://github.com/ricardojoserf/lsass-dumper-csharp): Custom lsass.exe dump using C#: XOR-encoding, Dynamic function resolution, using NTAPIs...

- [MinidumpParser](https://github.com/ricardojoserf/MinidumpParser) - C# program to parse Microsoft Minidump files

- [NativeBypassCredGuard](https://github.com/ricardojoserf/NativeBypassCredGuard): Bypass Credential Guard by patching WDigest.dll using only NTAPI functions

- [NativeDump](https://github.com/ricardojoserf/NativeDump) - Dump lsass using only NTAPIs by hand-crafting Minidump files (without MinidumpWriteDump)

- [Non-ms-binaries](https://github.com/ricardojoserf/non-ms-binaries): Code snippet to create a process using the "PROCESS_CREATION_MITIGATION_POLICY_BLOCK_NON_MICROSOFT_BINARIES_ALWAYS_ON" flag

- [P-Invoke.net](https://github.com/ricardojoserf/p-invoke.net) - P/Invoke definitions from the now offline pinvoke.net - Website: [https://ricardojoserf.gitbook.io/pinvoke](https://ricardojoserf.gitbook.io/pinvoke)

- [SharpADS](https://github.com/ricardojoserf/SharpADS): Read, write and delete Alternate Data Streams (ADS) within NTFS, to hide malicious payloads

- [SharpCovertTube](https://github.com/ricardojoserf/SharpCovertTube): Youtube as covert-channel - Control Windows systems remotely and execute commands by uploading videos to Youtube

- [SharpEA](https://github.com/ricardojoserf/SharpEA): Read, write and delete Extended Attributes (EAs) within NTFS, to hide malicious payloads

- [SharpObfuscate](https://github.com/ricardojoserf/SharpObfuscate): Obfuscate payloads using IPv4, IPv6, MAC or UUID strings

- [SharpNtdllOverwrite](https://github.com/ricardojoserf/SharpNtdllOverwrite): Overwrite ntdll.dll ".text" section to bypass API hooking. Getting the clean ntdll.dll from disk, Knowndlls folder, a debugged process or a URL

- [SharpProcessDump](https://github.com/ricardojoserf/SharpProcessDump): Dump memory regions of a process using only native API calls (NtQueryVirtualMemory and NtReadVirtualMemory)

- [SharpSelfDelete](https://github.com/ricardojoserf/Sharpselfdelete): PoC to self-delete a binary in C#. The process continues but the .exe file is removed from disk

- [StealthyEnv](https://github.com/ricardojoserf/StealthyEnv): Stealthier alternative to whoami.exe in C#, it gets environment variables from PEB (PRTL_USER_PROCESS_PARAMETERS)

- [TrickDump](https://github.com/ricardojoserf/TrickDump): Dump lsass using only NTAPIS running 3 programs to create 3 JSON and 1 ZIP file... and generate the Minidump later!

- [WhoamiAlternatives](https://github.com/ricardojoserf/WhoamiAlternatives): Different methods to get current username without using whoami, based on vx-underground posts


<p align="center">
  <img width="420" src="https://raw.githubusercontent.com/ricardojoserf/ricardojoserf.github.io/master/images/sharpnado/test2.drawio.png">
</p>
