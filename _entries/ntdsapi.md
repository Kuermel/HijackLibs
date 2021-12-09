---
Name: ntdsapi.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\certutil.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\cipher.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\gpresult.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\nltest.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\w32tm.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
