---
Name: cabinet.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\bootim.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\certutil.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\cmdl32.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\expand.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\extrac32.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\licensingdiag.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\makecab.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\msdt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\musnotification.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\musnotificationux.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\netsh.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\plasrv.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\reagentc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\recdisc.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\relpost.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\resetengine.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\sdclt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\systemreset.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\usocoreworker.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wextract.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wimserv.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wpnpinst.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

