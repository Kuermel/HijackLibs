---
Name: srvcli.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\change.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\chglogon.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\chgport.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\driverquery.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\eventcreate.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\getmac.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\gpresult.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\ksetup.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\net.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\net1.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\openfiles.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\query.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\quser.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\qwinsta.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\reset.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rwinsta.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\spaceagent.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\systempropertiesadvanced.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\taskkill.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\tasklist.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\tscon.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\tskill.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\waitfor.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wbengine.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

