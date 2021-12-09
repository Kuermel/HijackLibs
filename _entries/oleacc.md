---
Name: oleacc.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\bootim.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\cttune.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\devicepairingwizard.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\easeofaccessdialog.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\fsquirt.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\magnify.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\optionalfeatures.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\osk.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\psr.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\utilman.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wmpdmc.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

