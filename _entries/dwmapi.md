---
Name: dwmapi.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\certreq.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\devicepairingwizard.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\displayswitch.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\dxpserver.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\fsquirt.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\gamepanel.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\lockscreencontentserver.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\osk.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rdpclip.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rdpshell.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rdvghelper.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wmpdmc.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---

