---
Name: sspicli.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\at.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\calc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\certreq.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\certutil.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\computerdefaults.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\dialer.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\driverquery.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\dsregcmd.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\edpcleanup.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\eduprintprov.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\eventcreate.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\fodhelper.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\ftp.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\getmac.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\gpresult.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\ksetup.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\mdeserver.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\msdt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\mshta.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\msra.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\mstsc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\mtstocom.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\muiunattend.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\netsh.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\openfiles.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\perfmon.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\pinenrollmentbroker.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\presentationsettings.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\psr.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\quickassist.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rdpsa.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\rpcping.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\sdclt.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\shutdown.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\systeminfo.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\systemsettingsadminflows.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\takeown.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\taskkill.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\tasklist.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\waitfor.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\whoami.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wkspbroker.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wlrmdr.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
