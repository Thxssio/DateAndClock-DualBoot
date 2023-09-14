<h1 align="center"> DateAndClock-DualBoot</h1>


***Correction of time difference between Windows and Ubuntu***

Windows 32 bits
```
  Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t       REG_DWORD /d 1
```
Windows 64 bits
```
  Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t       REG_QWORD /d 1
```
