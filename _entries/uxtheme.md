---
Name: uxtheme.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\cttune.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\displayswitch.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\ehstorauthn.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\filehistory.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\gamepanel.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\msdt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\msra.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\quickassist.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\sdclt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\taskmgr.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\wfs.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wiaacmgr.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wiawow64.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wmpdmc.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
