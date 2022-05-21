---
Name: wevtapi.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\gpupdate.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\netsh.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\packageinspector.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\plasrv.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wecutil.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wsreset.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\filehistory.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\logman.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
- https://wietze.github.io/blog/save-the-environment-variables
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

