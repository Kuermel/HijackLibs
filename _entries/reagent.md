---
Name: reagent.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\bootim.exe'
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
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
