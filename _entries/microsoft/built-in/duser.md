---
Name: duser.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
  - "%SYSTEM32%"
  - "%SYSWOW64%"
VulnerableExecutables:
  - Path: '%SYSTEM32%\rekeywiz.exe'
    Type: Sideloading
Resources:
  - https://wietze.github.io/blog/hijacking-dlls-in-windows
  - https://twitter.com/0xcarnage/status/1203882560176218113
Acknowledgements:
  - Name: Wietze
    Twitter: "@wietze"
---

