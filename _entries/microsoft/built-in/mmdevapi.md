---
Name: mmdevapi.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\osk.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\certreq.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\devicecensus.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\mblctr.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\notepad.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\presentationsettings.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\sndvol.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
- https://wietze.github.io/blog/save-the-environment-variables
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

